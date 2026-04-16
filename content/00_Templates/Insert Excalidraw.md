<%*
const defaultTitle = tp.date.now("YYYYMMDDHHmm") + ' ' + tp.file.title;
const title = await tp.system.prompt("Drawing title?", defaultTitle);
const excalidrawFolder = "01_Excalidraw";
const transcludePath = excalidrawFolder + '/' + title;
tR = '![[' + transcludePath + '.excalidraw.svg]]';
const ea = ExcalidrawAutomate;
ea.reset();
await ea.create({
  filename: title,
  foldername: excalidrawFolder,
  onNewPane: true
});
%>