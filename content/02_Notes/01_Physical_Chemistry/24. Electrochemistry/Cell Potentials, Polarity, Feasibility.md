# Calculating $\mathrm{E^{⦵}_{\text{cell}}}$
>[!concept] Cell Polarity
>When two half-cells are connected:
>1. **More positive $\mathrm{E^{⦵}}$ = Reduction (Cathode) = Positive Pole (Gain Electrons)**
>2. **More negative $\mathrm{E^{⦵}}$ = Oxidation (Anode) = Negative Pole (Loses Electrons)**

>[!tip] Tip: Useful Mnemonics
>1. **Red Cat** $\to$ Reduction occurs at Cathode
>2. **An Ox** $\to$ Oxidation occurs at Anode
>3. **OIL RIG** $\to$ Oxidation is loss of electrons, Reduction is gain of electrons

>[!math] Calculating $\mathrm{E^{⦵}_{\text{cell}}}$
>$$\mathrm{E^{⦵}_{\text{cell}}} = \mathrm{E^{⦵}_{\text{positive}}} - \mathrm{E^{⦵}_{\text{negative}}}$$

# Direction of Electron Flow
>[!concept] Direction of Electron Flow
>Electrons flow from Anode (Negative) to Cathode (Positive).

# Feasibility 
>[!info] Feasibility
>A reaction is **feasible (spontaneous)** if the $\mathrm{E^{⦵}_{\text{cell}}}$ is positive.

A reaction is **feasible** or **spontaneous** if it can occur by itself under standard conditions without the need for continuous external energy (like a power supply) to force it to happen.

In electrochemistry, the feasibility of a reaction is determined by the **Standard Electrode Potentials** ($\mathrm{E^{⦵}}$) of the two-half cells involved.

>[!concept] More Positive $\mathrm{E^{⦵}}$ = Higher Oxidising Power
>- The species on the left-hand-side of the half-equation strongly attracts electrons.
>- It has a high **tendency to be reduced** (gain electrons) and acts as a strong oxidising agent.
>
>**Recall:** An oxidising agent causes oxidation in other species and is itself reduced, so the more it likes to be reduced the stronger it is at oxidising others.

>[!concept] More Negative $E^{⦵}$ = Higher Reducing Power
>- The species on the right-hand-side of the half-equation is highly willing to lose its electrons.
>- It has a high **tendency to be oxidised** (lose electrons) and acts as a strong oxidising agent.
>  
>**Recall:** A reducing agent causes reduction in other species and is itself oxidised, so the more it likes to be oxidised the stronger it is at reducing others.

When two half-cells are connected, the species in the half-cell with the **more positive $\mathrm{E^{⦵}}$** has a higher oxidising power. It will pull electrons towards itself and undergo **reduction** (acting as a cathode). Conversely, the species in the half-cell with the **more negative $\mathrm{E^{⦵}}$** will lose electrons and undergo **oxidation** (acting as anode).

For a spontaneous reaction, the overall cell potential is calculated as:
$$
\mathrm{E^{⦵}_{\text{cell}} = E^{⦵}_{\text{reduction}}-E^{⦵}_{\text{oxidation}}}
$$
Because the spontaneous direction ([[Clockwise Method]]) always involves subtracting the smaller (more negative) value from the larger (more positive) value, a spontaneous reaction will always yield a **positive $\mathrm{E^{⦵}_{\text{cell}}}$**.

If you attempt to reverse the reaction, you are forcing the stronger oxidising agent to be oxidised, and the stronger reducing agent to be reduced. This goes against thermodynamics. Therefore, the reaction is **not spontaneous** and will only occur if you continuously input energy into the system.

Mathematically, reversing the reaction swaps the roles of the cathode and anode. Calculating the new $\mathrm{E^{⦵}_{\text{cell}}}$ now requires subtracting a more positive value from a more negative value. This results in a **negative $\mathrm{E^{⦵}_{\text{cell}}}$**.

## Gibbs Free Energy ($\Delta \mathrm{G^{⦵}}$)
There is a direct mathematical link between the standard cell potential and the standard Gibbs free energy:

$$\Delta G^\ominus = -n F E^\ominus_{\text{cell}}$$

- $\Delta \mathrm{G^{⦵}}$ = Standard Gibbs Free Energy Change ($\text{J mol}^{-1}$ - Divide by 1000 for $\text{kJ mol}^{-1}$).
- $n$ = Number of moles of electrons transferred in the balanced overall equation.
- $F$ = Faraday's Constant, Total electrical charge of one mole of electrons ($96 500 \text{ C mol}^{-1}$).
- $\mathrm{E^{⦵}_{\text{cell}}}$ = Standard Cell Potential.

> [!math]- Derivation of $\Delta G^\ominus = -n F E^\ominus_{\text{cell}}$ (Not Required)
> **1. The Definition of Electrical Work**
> In physics, the electrical work done (energy released) by moving a charge through a voltage is:
> $$\text{Electrical Energy} = \text{Total Charge} \times \text{Voltage}$$
> 
> **2. Finding the "Total Charge" ($Q$)**
> In a chemical cell, the charge is carried by electrons. 
> If $n$ moles of electrons flow through the circuit, and 1 mole of electrons has a charge of $F$ ($96,500\text{ C}$), the total charge moved is:
> $$\text{Total Charge} = n \times F$$
> 
> **3. Finding the "Voltage" ($V$)**
> The voltage pushing those electrons is simply the cell potential, $E^\ominus_{\text{cell}}$.
> 
> **4. Combining them into Energy**
> Substitute the charge and voltage back into the first equation:
> $$\text{Maximum Electrical Energy Output} = (n \times F) \times E^\ominus_{\text{cell}}$$
> 
> **5. Linking it to Gibbs Free Energy ($\Delta G$)**
> By definition, $\Delta G$ is the maximum amount of "useful work" a chemical system can do. 
> * When a cell runs spontaneously, it **releases** energy to the surroundings (it does work). 
> * In thermodynamics, when a system loses energy, the change is **negative**. 
> * Therefore, to make the signs match, we add a minus sign:
> $$\Delta G^\ominus = -n F E^\ominus_{\text{cell}}$$

| Electrochemistry Rule                            | Thermodynamics Rule                            | Result                                      |
| :----------------------------------------------- | :--------------------------------------------- | :------------------------------------------ |
| $E^\ominus_{\text{cell}}$ is **Positive** ($>0$) | $\Delta G^\ominus$ becomes **Negative** ($<0$) | Reaction is **Spontaneous / Feasible**      |
| $E^\ominus_{\text{cell}}$ is **Negative** ($<0$) | $\Delta G^\ominus$ becomes **Positive** ($>0$) | Reaction is **Not Feasible**                |
| $E^\ominus_{\text{cell}}$ is **Zero** ($0$)      | $\Delta G^\ominus$ becomes **Zero** ($0$)      | System is at **Equilibrium** (Flat battery) |
