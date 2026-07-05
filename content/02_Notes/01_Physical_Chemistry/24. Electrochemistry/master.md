Here is a comprehensive, Obsidian-optimised master note file for **9701 A Level Chemistry: Chapter 24 - Electrochemistry**. 

It has been synthesized using the provided SaveMyExams notes, Collins textbook insights, exact syllabus requirements, and crucial examiner commentary based on the provided mark schemes.

***

# 🔋 Chapter 24: Electrochemistry

> [!info] Chapter Overview
> Electrochemistry links chemical energy to electrical energy. This topic is split into two main sections:
> 1. **Electrochemical Cells (Galvanic/Voltaic):** Chemical reactions *produce* an electrical voltage (spontaneous).
> 2. **Electrolytic Cells:** Electrical voltage *drives* a chemical reaction (non-spontaneous).

---

## 1. Standard Electrode Potentials ($E^\ominus$)

### Definitions (Strict CIE Mark Scheme Phrasing)
To secure the marks in the exam, your definitions must be perfectly aligned with the syllabus.

> [!abstract] Standard Electrode Potential ($E^\ominus$)
> The potential difference (voltage) of a half-cell compared to, or connected to, a **standard hydrogen electrode (SHE)** under standard conditions.

> [!abstract] Standard Cell Potential ($E^\ominus_{\text{cell}}$)
> The potential difference between two half-cells/electrodes in an electrochemical cell measured under standard conditions.

**Standard Conditions:**
*   **Temperature:** 298 K ($25^\circ C$)
*   **Pressure:** 101 kPa (1 atm) for any gases
*   **Concentration:** $1.00 \text{ mol dm}^{-3}$ for all aqueous ions.
    *   *Examiner Trap:* If using $H_2SO_4$ for $H^+$ ions, the concentration of the acid must be **$0.50 \text{ mol dm}^{-3}$** because it is diprotic ($H_2SO_4 \rightarrow 2H^+ + SO_4^{2-}$).

### The Standard Hydrogen Electrode (SHE)
Because you cannot measure the absolute potential of a single half-cell, we measure everything against the SHE, which is arbitrarily assigned a value of **$0.00 \text{ V}$**.

![Standard Hydrogen Electrode](https://s3.eu-west-2.amazonaws.com/elements.cognitoedu.org/031368d8-20e7-4689-91a1-e47e23245a8a/standard-hydrogen-electrode-diagram.png)

*   **Electrode:** Platinised Platinum (Pt). *Why Pt?* It is inert, conducts electricity, and provides a surface area for the redox equilibrium to occur without taking part in the reaction itself.
*   **Reaction:** $2H^+_{(aq)} + 2e^- \rightleftharpoons H_{2(g)} \quad E^\ominus = 0.00 \text{ V}$

---

## 2. Types of Half-Cells and Measuring $E^\ominus$

When drawing or describing apparatus to measure $E^\ominus$, you must connect the half-cell to the SHE via a **salt bridge** and a **high-resistance voltmeter**. 

> [!tip] The Salt Bridge
> Usually filter paper soaked in saturated **Potassium Nitrate ($KNO_3$)** or Potassium Chloride ($KCl$). 
> *   **Purpose:** Completes the circuit by allowing mobile ions to flow, maintaining ionic balance.
> *   *Why $KNO_3$?* Nitrates are universally soluble, ensuring no precipitates form which would alter ion concentrations and shift the equilibrium.

### Type 1: Metal / Metal Ion
E.g., $Cu^{2+}_{(aq)} / Cu_{(s)}$
*   The metal itself acts as the electrode.
*   Dipped in a $1.0 \text{ mol dm}^{-3}$ solution of its ions.

### Type 2: Non-Metal / Non-Metal Ion
E.g., $Cl_{2(g)} / Cl^-_{(aq)}$
*   Requires an inert **Platinum (Pt)** electrode.
*   Gas is bubbled at 1 atm into a $1.0 \text{ mol dm}^{-3}$ solution of the ions.

### Type 3: Ion / Ion (Different Oxidation States)
E.g., $Fe^{3+}_{(aq)} / Fe^{2+}_{(aq)}$ or $MnO_4^-_{(aq)} / Mn^{2+}_{(aq)}$
*   Requires an inert **Platinum (Pt)** electrode.
*   **Crucial:** Both ions must be present in the solution at $1.0 \text{ mol dm}^{-3}$. (e.g., A mixture containing $1.0 \text{ M}$ $Fe^{2+}$ AND $1.0 \text{ M}$ $Fe^{3+}$).

![Ion/Ion Half Cell](https://cdn.savemyexams.com/uploads/2025/06/10376_httpscdn-savemyexams-comuploads2021015-3-principles-of-electrochemistry-example-of-an-ion--ion-half-cell.png)

---

## 3. Cell Potentials, Polarity, and Feasibility

### Calculating $E^\ominus_{\text{cell}}$
When two half-cells are connected:
1.  **Most positive $E^\ominus$ = Reduction (Cathode) = Positive Pole** (Gains electrons)
2.  **Most negative $E^\ominus$ = Oxidation (Anode) = Negative Pole** (Loses electrons)

$$E^\ominus_{\text{cell}} = E^\ominus_{\text{reduction}} - E^\ominus_{\text{oxidation}}$$
*(Or simply: More positive value minus less positive value)*

> [!example] Direction of Electron Flow
> Consider $Zn^{2+}/Zn$ ($-0.76 \text{ V}$) and $Cu^{2+}/Cu$ ($+0.34 \text{ V}$).
> *   $Cu^{2+}$ is more positive: Reduction occurs here. Positive Pole.
> *   $Zn$ is more negative: Oxidation occurs here. Negative Pole.
> *   **Electron Flow:** Through the external wires from Negative ($Zn$) to Positive ($Cu$).

### Feasibility of a Reaction
A reaction is **feasible (spontaneous)** if the calculated $E^\ominus_{\text{cell}}$ is **positive**. 

### Gibbs Free Energy ($\Delta G^\ominus$)
There is a direct mathematical link between the standard cell potential and the standard Gibbs free energy:

$$\Delta G^\ominus = -n F E^\ominus_{\text{cell}}$$

*   **$\Delta G^\ominus$** = Standard Gibbs free energy change (**Joules, J mol$^{-1}$** — *Divide by 1000 for kJ!*)
*   **$n$** = Number of moles of electrons transferred in the balanced overall equation.
*   **$F$** = Faraday constant ($96,500 \text{ C mol}^{-1}$)
*   **$E^\ominus_{\text{cell}}$** = Standard cell potential (V)

> [!warning] Classic Exam Error
> The equation gives $\Delta G$ in **Joules**. CIE questions almost always ask for the answer in **kJ mol$^{-1}$**. Do not forget to divide your final answer by 1000!
> Also, ensure you attach the correct sign: if $E^\ominus_{\text{cell}}$ is positive, $\Delta G$ MUST be negative.

---

## 4. Non-Standard Conditions: The Nernst Equation

If concentrations are NOT $1.0 \text{ mol dm}^{-3}$, the position of equilibrium shifts (Le Chatelier's Principle), which alters the electrode potential ($E$). 

We calculate the exact new potential using the **Nernst Equation**:

$$E = E^\ominus + \frac{0.059}{z} \log_{10} \frac{[\text{oxidised species}]}{[\text{reduced species}]}$$

*   **$E$** = Electrode potential under non-standard conditions
*   **$E^\ominus$** = Standard electrode potential (from Data Booklet)
*   **$z$** = Number of electrons transferred in the half-equation
*   **$[\text{oxidised}]$** = Concentration of the species on the side of the half-equation *with* the electrons (usually the left).
*   **$[\text{reduced}]$** = Concentration of the species on the side *without* electrons.

> [!tip] Nernst Equation Rules
> *   **Solids and liquids are ignored** (their concentration is given a value of 1).
> *   If a species has a molar coefficient in the half-equation (e.g., $2Br^-$), its concentration must be raised to that power (e.g., $[Br^-]^2$).

**Qualitative Nernst (Le Chatelier):**
Given $Cu^{2+}_{(aq)} + 2e^- \rightleftharpoons Cu_{(s)} \quad E^\ominus = +0.34 \text{ V}$
*   If we *add water* (dilute the solution), $[Cu^{2+}]$ decreases. 
*   Equilibrium shifts to the **left** to oppose the change.
*   The species gets *less easily reduced*, so $E$ becomes **less positive** (e.g., $+0.28 \text{ V}$).

---

## 5. Electrolysis

Electrolysis uses direct current (DC) to break down an electrolyte.

### Predicting Products
When an aqueous solution is electrolysed, water provides $H^+$ and $OH^-$ ions, creating competition at the electrodes.

**At the Cathode (Negative Electrode) - Reduction:**
*   Competitors: Metal cation (e.g., $Na^+$) vs $H^+$.
*   **Rule:** The species with the **most positive $E^\ominus$** is discharged.
*   *Result:* Unreactive metals ($Cu, Ag$) are discharged. Reactive metals ($Na, Mg, Al$) stay in solution, and $H_2$ gas is discharged instead.

**At the Anode (Positive Electrode) - Oxidation:**
*   Competitors: Anion (e.g., $Cl^-, SO_4^{2-}$) vs $OH^-$.
*   **Rule:** The species with the **most negative $E^\ominus$** is most easily oxidised.
*   **THE CONCENTRATION CATCH:** 
    *   $OH^- \rightarrow O_2 + H_2O + 4e^-$ ($E^\ominus = +0.40 \text{ V}$)
    *   $Cl^- \rightarrow Cl_2 + 2e^-$ ($E^\ominus = +1.36 \text{ V}$)
    *   *Normally*, $OH^-$ should discharge to give $O_2$ (it is much more negative). However, if the halide is **concentrated**, the Nernst shift makes the Halide discharge instead!
    *   *Dilute NaCl:* $O_2$ produced.
    *   *Concentrated NaCl:* $Cl_2$ produced.

### Faraday's Laws & Calculations
*   **Quantity of Charge ($Q$):** $Q = I \times t$
    *   $Q$ = Charge in Coulombs (C)
    *   $I$ = Current in Amperes (A)
    *   $t$ = Time in **seconds (s)**
*   **Faraday Constant ($F$):** The charge of 1 mole of electrons. $F = 96,500 \text{ C mol}^{-1}$
*   **Avogadro Constant ($L$):** $F = L \times e$ (where $e$ is the charge of a single electron, $1.60 \times 10^{-19} \text{ C}$).

**Calculation Steps for Mass/Volume Liberated:**
1.  Calculate $Q = It$.
2.  Calculate moles of electrons: $n(e^-) = \frac{Q}{96500}$.
3.  Use the half-equation to find the molar ratio of electrons to product.
4.  Calculate moles of product $\rightarrow$ convert to mass ($m = n \times M_r$) or volume ($V = n \times 24.0 \text{ dm}^3$).

---

## 6. Determining Avogadro's Constant ($L$) Experimentally

This is a specific syllabus requirement and a classic Paper 4/Paper 5 question.

**Apparatus:**
*   Pure copper anode and cathode.
*   Aqueous Copper(II) Sulfate electrolyte.
*   DC power supply, ammeter, variable resistor (to keep current constant).

![Determining Avogadro](https://s3.eu-west-2.amazonaws.com/elements.cognitoedu.org/882226e9-0a29-4928-9811-2282d512e3ed/electrolysis-apparatus-avogadro-constant.png)

**Method:**
1.  Weigh the pure copper **anode** before the experiment.
2.  Pass a known constant current ($I$) for a known time ($t$ in seconds).
3.  Remove the anode, wash with distilled water, dry with propanone (evaporates quickly), and **reweigh**.
4.  Calculate mass lost by anode $\rightarrow$ calculate moles of Cu dissolved ($n = \frac{m}{63.5}$).

**Calculation:**
*   Half equation: $Cu_{(s)} \rightarrow Cu^{2+}_{(aq)} + 2e^-$ (1 mol Cu releases 2 mol $e^-$).
*   Moles of electrons passed = $n(Cu) \times 2$.
*   Total charge $Q = It$.
*   Charge of 1 mole of electrons (Faraday, $F$) = $\frac{Q}{\text{moles of } e^-}$
*   Avogadro's Constant $L = \frac{F}{\text{charge of 1 electron } (1.60 \times 10^{-19})}$

> [!tip] Why use the Anode?
> Past papers frequently ask why we measure the mass loss of the anode rather than the mass gain of the cathode. 
> *Answer:* Copper deposited at the cathode does not always stick properly and can flake off, leading to inaccurate (lower) mass readings. The mass lost from the anode is a much more reliable metric.

---

## 7. 🕵️‍♂️ The Examiner's Vault: Past Paper Tropes & Traps

Based on an analysis of the 2009–2022 Paper 4 question bank, pay close attention to these highly repetitive concepts:

### Trope 1: Fuel Cells (e.g., Hydrogen-Oxygen)
*   **Question:** "Suggest why the voltage of the fuel cell remains constant."
*   **Mark Scheme Answer:** The reagents (fuel and oxygen) are being continuously supplied / fed in, and concentration of the electrolyte remains constant.

### Trope 2: Disproportionation
*   **Question context:** They will give you a species like $H_2O_2$ or $ClO_2$ and ask you to prove it disproportionates using $E^\ominus$ values.
*   **Action:** Find the two half-equations where the species acts as an oxidising agent (gets reduced) and a reducing agent (gets oxidised). Calculate $E^\ominus_{\text{cell}}$. If positive, it disproportionates.

### Trope 3: Drawing Cells with Specificity
*   If asked to draw a cell to measure the $E^\ominus$ of $Fe^{3+}/Fe^{2+}$, you will lose marks if you do not explicitly label the solution as containing **$1.0 \text{ mol dm}^{-3}$ of $Fe^{3+}$ AND $1.0 \text{ mol dm}^{-3}$ of $Fe^{2+}$**. 
*   **Must include:** Salt bridge, Voltmeter, Pt electrode, Standard Hydrogen Electrode (with $1 \text{ atm } H_2$ and $1 \text{ M } H^+$).

### Trope 4: The Nernst Equation Trap
*   **Question:** Calculate $E$ for the $Ag^+ / Ag$ electrode when $[Ag^+] = 0.012 \text{ mol dm}^{-3}$.
*   **Mistake:** Students try to put $Ag_{(s)}$ into the Nernst equation.
*   **Mark Scheme Answer:** Solids are omitted! 
    $E = 0.80 + \frac{0.059}{1} \log_{10} [\text{0.012}]$ (Because the solid Ag acts as a 1).

### Trope 5: "State the relationship between F, L and e"
*   **Mark Scheme Answer:** $F = L \times e$ (or $L = F/e$). 1 mark. Free points, do not forget this simple formula.

### Trope 6: Justifying Relative Reactivity
*   **Question:** "Use the Data Booklet to explain why silver remains as a metal but nickel dissolves at the anode during purification."
*   **Action:** Quote the $E^\ominus$ values! 
    *   $Ag^+ + e^- \rightleftharpoons Ag \quad E^\ominus = +0.80 \text{ V}$
    *   $Ni^{2+} + 2e^- \rightleftharpoons Ni \quad E^\ominus = -0.25 \text{ V}$
    *   **Mark Scheme phrasing:** "$E^\ominus$ for $Ag^+/Ag$ is more positive than $E^\ominus$ for $Ni^{2+}/Ni$ / or $Cu^{2+}/Cu$, so Ag is less easily oxidised / prefers to remain reduced as a solid."
