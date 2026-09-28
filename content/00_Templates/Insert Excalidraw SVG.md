<%*
const filename = await tp.system.prompt("Enter drawing filename:");
if (!filename) return;

const plugin = app.plugins.plugins["obsidian-excalidraw-plugin"];
if (!plugin) { new Notice("Excalidraw plugin is not enabled."); return; }

const folderPath = plugin.settings.folder || "";
if (folderPath) {
    try {
        await app.vault.createFolder(folderPath);
    } catch (e) {
        // Folder already exists — safe to ignore
    }
}

const filePath = folderPath ? `${folderPath}/${filename}.md` : `${filename}.md`;
let file = app.vault.getAbstractFileByPath(filePath);

if (!file) {
    const drawing = {
        type: "excalidraw",
        version: 2,
        source: "obsidian",
        elements: [],
        appState: { gridSize: null, viewBackgroundColor: "#ffffff" },
        files: {}
    };
    const templateContent = [
        "---",
        "excalidraw-plugin: parsed",
        "tags: [excalidraw]",
        "---",
        "==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==",
        "",
        "# Excalidraw Data",
        "",
        "## Text Elements",
        "%%",
        "## Drawing",
        "```json",
        JSON.stringify(drawing),
        "```",
        "%%"
    ].join("\n");
    file = await app.vault.create(filePath, templateContent);
} else {
    new Notice("Drawing already exists. Inserting link and opening it.");
}

tR += `![${filename}|500](${filename}.svg)`;

setTimeout(async () => {
    const leaf = app.workspace.getLeaf("tab");
    await leaf.openFile(file);
    if (plugin.excalidrawFileModes) {
        plugin.excalidrawFileModes[leaf.id || file.path] = "excalidraw";
    }
    await leaf.setViewState({ type: "excalidraw", state: leaf.view.getState() });
}, 150);
%>