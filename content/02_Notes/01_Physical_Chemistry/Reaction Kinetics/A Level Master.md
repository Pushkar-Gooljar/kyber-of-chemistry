
---

# Chapter 26: Reaction Kinetics (Cambridge A-Level Chemistry 9701)

> [!info] Syllabus Context
> This comprehensive note covers Section 26 of the CIE 9701 A-Level Chemistry syllabus (for 2025-2027). It bridges theoretical principles (orders, rate equations, mechanisms, catalysts) with high-yield exam calculation techniques and past-paper mark scheme terminology.

---

## 1. Fundamental Concepts & Terminology

*   **Rate of Reaction**: The change in concentration (or amount) of a reactant or product per unit time. 
    *   Formula: $\text{Rate} = \frac{\Delta \text{Concentration}}{\Delta \text{Time}}$
    *   Units: $\text{mol dm}^{-3} \text{ s}^{-1}$
*   **Rate Equation**: A mathematically determined equation showing how the rate of reaction depends on the concentrations of reactants. 
    *   General form: $\text{Rate} = k[A]^m[B]^n$
    *   *Note: Rate equations can **only** be determined experimentally, not from stoichiometric equations.*
*   **Rate Constant ($k$)**: A proportionality constant in the rate equation. It is constant at a fixed temperature but increases if temperature increases.
*   **Order of Reaction (with respect to a reactant)**: The power to which the concentration of that reactant is raised in the rate equation (i.e., $m$ or $n$). It shows how a reactant's concentration affects the rate.
*   **Overall Order of Reaction**: The sum of the powers of the concentration terms in the rate equation ($m + n$).
*   **Half-Life ($t_{1/2}$)**: The time taken for the concentration of a limiting reactant to fall to half of its initial value.

---

## 2. Determining Orders of Reaction

The order of a reactant (0, 1, or 2) can be deduced using concentration–time graphs, rate–concentration graphs, the half-life method, or initial rate tables.

### Reaction Order Grid Summary
![Reaction Order Grid](https://s3.eu-west-2.amazonaws.com/elements.cognitoedu.org/7404157d-aa19-451b-b7f0-cf068583d47c/reaction-order-rate-concentration-graphs.png)

### Concentration-Time Graphs

| Zero Order | First Order | Second Order |
| :--- | :--- | :--- |
| Concentration decreases at a constant rate. | Concentration decreases as a smooth curve with a **constant half-life**. | Concentration decreases as a steeper curve. Successive half-lives *increase*. |
| ![0 order C-T](https://cdn.savemyexams.com/uploads/2025/06/54847_httpscdn-savemyexams-comuploads2021015-6-reaction-kinetics-zero-order-concentration.png) | ![1st order C-T](https://cdn.savemyexams.com/uploads/2025/06/35183_httpscdn-savemyexams-comuploads2021015-6-reaction-kinetics-first-order-concentration.png) | ![2nd order C-T](https://cdn.savemyexams.com/uploads/2025/06/35604_httpscdn-savemyexams-comuploads2021015-6-reaction-kinetics-second-order-concentration.png) |

### Rate-Concentration Graphs

| Zero Order | First Order | Second Order |
| :--- | :--- | :--- |
| Rate is independent of concentration (horizontal line). Rate = $k$. | Rate is directly proportional to concentration (straight line through origin). Rate = $k[A]$. | Rate is directly proportional to the *square* of concentration (curved line). Rate = $k[A]^2$. |
| ![0 order R-C](https://cdn.savemyexams.com/uploads/2025/06/58156_httpscdn-savemyexams-comuploads2021015-6-reaction-kinetics-zero-order-rate.png) | ![1st order R-C](https://cdn.savemyexams.com/uploads/2025/06/58855_httpscdn-savemyexams-comuploads2021015-6-reaction-kinetics-first-order-rate.png) | ![2nd order R-C](https://cdn.savemyexams.com/uploads/2025/06/38930_httpscdn-savemyexams-comuploads2021015-6-reaction-kinetics-second-order-rate.png) |

### Half-Life ($t_{1/2}$) and Orders

![Half Lives](https://cdn.savemyexams.com/uploads/2025/06/56892_httpscdn-savemyexams-comuploads2021015-6-reaction-kinetics-half-life.png)
*   **Zero Order**: $t_{1/2}$ decreases as reaction progresses.
*   **First Order**: $t_{1/2}$ is **constant** and independent of concentration.
*   **Second Order**: $t_{1/2}$ increases as reaction progresses.

#### First Order Rearrangement Example
The rearrangement of the methyl group in ethanenitrile ($\text{CH}_3\text{CN}$) is a classic first-order process:
$$\text{CH}_3\text{CN}(g) \rightarrow \text{CH}_3\text{NC}(g)$$
![Methyl Group Rearrangement](https://cdn.savemyexams.com/uploads/2021/02/5.6-Reaction-Kinetics-Rearrangement-of-Methyl-Group.png)

> [!example] Calculating First-Order Rate Constant from Half-Life
> For a first-order reaction, $k$ and $t_{1/2}$ are related by the equation:
> $$k = \frac{0.693}{t_{1/2}}$$
> *Example (Methyl rearrangement):* If the half-life on a graph is constantly 10 minutes:
> $$k = \frac{0.693}{10 \times 60 \text{ s}} = 1.16 \times 10^{-3} \text{ s}^{-1}$$
> ![1st Order Half Life Graph](https://cdn.savemyexams.com/uploads/2025/06/3154_httpscdn-savemyexams-comuploads2021015-6-reaction-kinetics-half-life-first-order.png)
> 
> *Alternative Example (Hydrogen Peroxide Decomposition):*
> Looking at the decomposition of $\text{H}_2\text{O}_2$:
> ![H2O2 Decomposition](https://s3.eu-west-2.amazonaws.com/elements.cognitoedu.org/d17ac5a6-8949-4cce-8dba-213f801d53cf/hydrogen-peroxide-decomposition-graph.png)
> Here, successive half-lives are constant at $100\text{ s}$ ($t_{1/2} = 100\text{ s}$):
> $$k = \frac{0.693}{100\text{ s}} = 6.93 \times 10^{-3}\text{ s}^{-1}$$

### The Initial Rates Method
1. Measure the initial rate by drawing a tangent at $t=0$ on a concentration-time curve ($\text{Rate} = \frac{\Delta Y}{\Delta X}$).
   ![Initial Rate Method Tangent](https://s3.eu-west-2.amazonaws.com/elements.cognitoedu.org/ab05b362-8fab-40a5-9cc6-6e0476d93f2a/initial-rate-method-graph.png)
2. Compare experiments where *only one* reactant's concentration changes:
    *   If concentration doubles and rate is **unchanged** $\rightarrow$ **Zero Order**
    *   If concentration doubles and rate **doubles** ($2^1$) $\rightarrow$ **First Order**
    *   If concentration doubles and rate **quadruples** ($2^2$) $\rightarrow$ **Second Order**

---

## 3. Rate Constant ($k$) Calculations & Units

To find the numerical value of $k$:
1. Write the rate equation (e.g., $\text{Rate} = k[A][B]^2$).
2. Rearrange for $k$: $k = \frac{\text{Rate}}{[A][B]^2}$
3. Substitute values from *one specific experiment row* in your data table.

**Deducing Units of $k$:**
Units are deduced by substituting the units into the rearranged equation and canceling them out.
$$k = \frac{\text{mol dm}^{-3}\text{s}^{-1}}{(\text{mol dm}^{-3}) \times (\text{mol dm}^{-3})^2} = \frac{\text{s}^{-1}}{(\text{mol dm}^{-3})^2} = \text{mol}^{-2}\text{dm}^6\text{s}^{-1}$$

---

## 4. Multi-Step Reactions & Mechanisms

Most reactions occur in a sequence of steps called a **reaction mechanism**.
*   **Rate-Determining Step (RDS)**: The slowest step in a reaction mechanism. It dictates the overall rate of reaction.
*   **Intermediate**: A species formed in one step of the mechanism and consumed in a subsequent step. (It does not appear in the overall chemical equation).
*   **Catalyst**: A species used in an early step and regenerated in a later step.

### Nucleophilic Substitution Mechanisms ($S_{\text{N}}1$ vs $S_{\text{N}}2$)
The rate-determining step can dictate whether a reaction proceeds via a one-step ($S_{\text{N}}2$) or multi-step ($S_{\text{N}}1$) pathway:

*   **$S_{\text{N}}2$ Mechanism (Bimolecular RDS - Single Step):**
    Both the halogenoalkane and the nucleophile collide in the rate-determining step.
    *   $\text{Rate} = k[\text{Halogenoalkane}][\text{OH}^-]$
    *   ![SN2 Mechanism](https://s3.eu-west-2.amazonaws.com/elements.cognitoedu.org/3ecaca1e-3bbd-4cc2-ad9d-7538287190f5/chloromethane-reaction-mechanism.png)

*   **$S_{\text{N}}1$ Mechanism (Unimolecular RDS - Two Steps):**
    Only the halogenoalkane is involved in the slow, rate-determining ionization step to form a stable carbocation intermediate.
    *   $\text{Rate} = k[\text{Halogenoalkane}]$
    *   ![SN1 Mechanism](https://s3.eu-west-2.amazonaws.com/elements.cognitoedu.org/600b5e9b-dc27-42c7-a370-ce8edcd7f2b4/chloromethane-substitution-mechanism.png)
    *   *Intermediate representation:*
        ![Halogenoalkane intermediate](https://cdn.savemyexams.com/uploads/2025/06/48799_httpscdn-savemyexams-comuploads2021015-6-reaction-kinetics-intermediate.png)

### Deducing the Mechanism from the Rate Equation
1. Any reactant in the rate equation **must** be present in the RDS (or in steps prior to the RDS).
2. The *order* of the reactant in the rate equation equals the *number of molecules* of that reactant involved in the RDS.
    *   *Example:* Rate = $k[NO]^2[H_2]$. The RDS must involve **two** molecules of $NO$ and **one** molecule of $H_2$.
    *   If a reactant is zero-order, it is involved in a step *after* the RDS.

#### Mechanism Example 1: Alkaline Bromination of Propane
*   Overall Reaction: $\text{CH}_3\text{CH}_2\text{CH}_3 + \text{Br}_2 + \text{OH}^- \rightarrow \text{CH}_3\text{CH}_2\text{CH}_2\text{Br} + \text{H}_2\text{O} + \text{Br}^-$
*   Rate Equation: $\text{Rate} = k[\text{CH}_3\text{CH}_2\text{CH}_3][\text{OH}^-]$
*   Mechanism:
    ![Propane Bromination Mechanism](https://cdn.savemyexams.com/uploads/2025/06/56239_httpscdn-savemyexams-comuploads2021025-6-reaction-kinetics-reaction-mechanism-bromination-propane.png)
    *Because $\text{Br}_2$ is not in the rate equation, it must react in a fast step after the RDS.*

#### Mechanism Example 2: Acid-Catalyzed Halogenation of Butanone
*   Overall Reaction: $\text{CH}_3\text{CH}_2\text{COCH}_3 + \text{I}_2 \xrightarrow{\text{H}^+} \text{CH}_3\text{CH}_2\text{COCH}_2\text{I} + \text{HI}$
*   Rate Equation: $\text{Rate} = k[\text{CH}_3\text{CH}_2\text{COCH}_3][\text{H}^+]$
*   Mechanism:
    ![Butanone Halogenation Mechanism](https://cdn.savemyexams.com/uploads/2025/06/55514_httpscdn-savemyexams-comuploads2022015-6-reaction-kinetics-reaction-mechanism-halogenation-butanone-1.png)
    *   *Intermediate formed in the RDS:*
        ![Butanone Intermediate](https://cdn.savemyexams.com/uploads/2025/06/1928_httpscdn-savemyexams-comuploads2021025-6-reaction-kinetics-intermediate-butanone.png)

---

## 5. Effect of Temperature on the Rate Constant

*   **Qualitative effect**: Increasing temperature increases the rate constant ($k$) and therefore the rate of reaction.
*   **Explanation**: At higher temperatures, a greater proportion of molecules possess kinetic energy equal to or greater than the activation energy ($E \geq E_a$). This leads to a higher frequency of *effective/successful* collisions.

> [!info] The Arrhenius Equation
> The relationship between $k$ and $T$ is given by:
> $$k = A e^{-\frac{E_a}{RT}}$$
> Taking the natural log gives a linear equation:
> $$\ln k = -\frac{E_a}{R}\left(\frac{1}{T}\right) + \ln A$$
> Plotting $\ln k$ (y-axis) against $\frac{1}{T}$ (x-axis) yields a straight line with a negative gradient equal to $-\frac{E_a}{R}$.
> ![Arrhenius Plot](https://cdn.savemyexams.com/uploads/2025/06/53908_httpscdn-savemyexams-comuploads2022015-2-5-arrhenius-sketch-of-ln-k-against-1-t-2.png)

### 5.1 Boltzmann Distribution Curves
Examiners regularly ask for a sketch of the Maxwell-Boltzmann distribution curves at two temperatures to illustrate why temperature significantly increases the rate constant $k$.

```
Number of 
Molecules
  |    ,-. (T1 - lower temperature)
  |   /   \
  |  /     \     ,-. (T2 - higher temperature)
  | /       \   /   \
  |/         `-/     `----------
  |_____________|_______________  Energy
               Ea
```

*   **Required Sketching Conventions:**
    1.  Both curves must start at the origin $(0,0)$.
    2.  The curve at the higher temperature ($T_2$) must have a **lower peak** and its peak must be shifted to the **right** (higher average kinetic energy).
    3.  The tail of the $T_2$ curve must lie entirely above the $T_1$ curve at the high-energy end.
    4.  Both curves must approach the x-axis asymptotically but never touch it.
    5.  A vertical line for Activation Energy ($E_a$) must be drawn. The shaded area under the curve to the right of $E_a$ represents the fraction of molecules with $E \ge E_a$. This area is visibly larger for $T_2$.

### 5.2 Mathematical Derivation of $E_a$ from Graph
When calculating the activation energy from an experimental $\ln k$ vs $\frac{1}{T}$ graph:
1. Identify two points on the line of best fit: $(x_1, y_1)$ and $(x_2, y_2)$ where $x = \frac{1}{T}$ and $y = \ln k$.
2. Calculate the gradient ($m$):
   $$m = \frac{\Delta y}{\Delta x} = \frac{\ln k_2 - \ln k_1}{\left(\frac{1}{T_2}\right) - \left(\frac{1}{T_1}\right)}$$
3. Use the relationship:
   $$\text{Gradient } (m) = -\frac{E_a}{R}$$
4. Solve for $E_a$:
   $$E_a = -m \times R \quad (\text{where } R = 8.31\text{ J K}^{-1}\text{ mol}^{-1})$$
5. *Note:* This calculation gives $E_a$ in $\text{J mol}^{-1}$. Divide by $1000$ to report the value in $\text{kJ mol}^{-1}$ as typically requested in Paper 4.

---

## 6. Homogeneous & Heterogeneous Catalysis

A catalyst increases the rate of reaction by providing an alternative reaction pathway with a lower activation energy ($E_a$).

### 6.1 Heterogeneous Catalysis
The catalyst is in a **different phase** from the reactants (usually a solid catalyst with gas/liquid reactants).

*   **General Mode of Action:**
    ![Heterogeneous Catalysis Steps](https://s3.eu-west-2.amazonaws.com/elements.cognitoedu.org/9391dcc4-dc84-4fc2-a0b8-dd2205baa264/2%20edit%402x.png)
    1.  **Adsorption** (Chemisorption): Reactant molecules diffuse to the solid surface and bond chemically to active sites.
    2.  **Activation (Bond Weakening)**: The formation of bonds between the reactant atoms and the catalyst surface weakens the internal covalent bonds of the reactants, lowering the activation energy barrier.
    3.  **Reaction**: Adsorbed species react on the surface to form product bonds.
    4.  **Desorption**: The bonds between the products and the catalyst surface break; the products diffuse away from the surface.

*   **Example 1: Haber Process**
    *   Reactants: $\text{N}_2(g) + 3\text{H}_2(g) \rightleftharpoons 2\text{NH}_3(g)$
    *   Catalyst: Solid **Iron ($\text{Fe}$)**.
    *   Mechanism:
        ![Haber Adsorption 1](https://cdn.savemyexams.com/uploads/2021/02/5.6-Reaction-Kinetics-Iron-Catalyst-1.png)
        ![Haber Adsorption 2](https://cdn.savemyexams.com/uploads/2025/06/27652_httpscdn-savemyexams-comuploads2021025-6-reaction-kinetics-iron-catalyst-2.png)

*   **Example 2: Catalytic Converters in Cars**
    *   Reactants: Pollutants like $\text{NO}_x$, $\text{CO}$, unburnt hydrocarbons.
    *   Catalyst: Honeycomb coated with **Palladium ($\text{Pd}$), Platinum ($\text{Pt}$), or Rhodium ($\text{Rh}$)**.
    *   Converts $\text{NO}_x$ to harmless $\text{N}_2$ gas and $\text{CO}$ to $\text{CO}_2$:
        ![Pd Catalysis Mechanism](https://cdn.savemyexams.com/uploads/2025/06/59279_httpscdn-savemyexams-comuploads2021025-6-reaction-kinetics-mode-of-action-heterogeneous-catalysis.png)

### 6.2 Homogeneous Catalysis
The catalyst is in the **same phase** as the reactants (often an aqueous ion or a gas). They usually work by forming an intermediate (undergoing a change in oxidation state) and being reformed in a later step.

*   **Example 1: The Iodine-Peroxydisulfate Reaction**
    *   Overall (very slow due to repulsive forces between two negative ions): 
        $$\text{S}_2\text{O}_8^{2-}(aq) + 2\text{I}^-(aq) \rightarrow 2\text{SO}_4^{2-}(aq) + \text{I}_2(aq)$$
    *   Catalyst: **$\text{Fe}^{2+}$ or $\text{Fe}^{3+}$** ions. They provide a pathway involving collisions between oppositely charged ions.
    *   Step 1: $\text{S}_2\text{O}_8^{2-} + 2\text{Fe}^{2+} \rightarrow 2\text{SO}_4^{2-} + 2\text{Fe}^{3+}$ ($\text{Fe}^{2+}$ is oxidised)
    *   Step 2: $2\text{Fe}^{3+} + 2\text{I}^- \rightarrow 2\text{Fe}^{2+} + \text{I}_2$ ($\text{Fe}^{3+}$ is reduced, reforming the catalyst)
    *   *Enthalpy Profile*: Notice the **two humps** representing the two activation energies for the two steps, with an intermediate dip.
    *   ![Homogeneous Enthalpy Profile 1](https://cdn.savemyexams.com/uploads/2025/06/27157_httpscdn-savemyexams-comuploads2021025-6-reaction-kinetics-energy-level-diagram-homogeneous-catalys.png)
    *   *Simplified Enthalpy Profile:*
        ![Homogeneous Enthalpy Profile 2](https://s3.eu-west-2.amazonaws.com/elements.cognitoedu.org/20379223-6a25-4147-a1a9-025403d3500b/homogeneous-catalysis-enthalpy-diagram.png)

*   **Example 2: Atmospheric $\text{NO}_x$ and Acid Rain**
    *   Overall: $\text{SO}_2(g) + \frac{1}{2}\text{O}_2(g) \rightarrow \text{SO}_3(g)$ (which reacts with $\text{H}_2\text{O}$ to form $\text{H}_2\text{SO}_4$)
    *   Catalyst: Nitrogen oxides (**$\text{NO}$ / $\text{NO}_2$**).
    *   Step 1: $\text{NO}_2(g) + \text{SO}_2(g) \rightarrow \text{NO}(g) + \text{SO}_3(g)$
    *   Step 2 (Regeneration): $\text{NO}(g) + \frac{1}{2}\text{O}_2(g) \rightarrow \text{NO}_2(g)$

### 6.3 Autocatalysis
Autocatalysis occurs when a product of a chemical reaction acts as a catalyst for that same reaction.

*   **Example: Oxidation of Ethanedioic Acid by Manganate(VII) Ions:**
    $$2\text{MnO}_4^-(aq) + 16\text{H}^+(aq) + 5\text{C}_2\text{O}_4^{2-}(aq) \rightarrow 2\text{Mn}^{2+}(aq) + 10\text{CO}_2(g) + 8\text{H}_2\text{O}(l)$$
    The $\text{Mn}^{2+}$ ions formed act as the homogeneous catalyst.
*   **Concentration-Time Profile of Autocatalysis:**
    Unlike normal reactions where the rate is fastest at $t=0$, autocatalyzed reactions exhibit a distinctive sigmoidal concentration-time curve:
    1.  *Initially Slow:* The reaction rate is slow because concentration of the catalyst ($\text{Mn}^{2+}$) is zero/low.
    2.  *Rapid Acceleration:* As $\text{Mn}^{2+}$ is generated, the rate increases rapidly (the curve steepens).
    3.  *Slowing Down:* Finally, as reactants are consumed, the rate decreases (the curve flattens).

---

## 7. Exam Gold: Worksheet Concepts & Mark Scheme Gems

This section distills exact phrasing and recurring tricks from Cambridge 9701 Paper 4 mark schemes. Master these to secure maximum marks.

### Deducing Orders from Tables
*   **Mark Scheme Phrasing for Justification**: Always state exactly what happens mathematically to both the concentration and the rate.
    *   *Example:* "Using Expts 1 and 2: $[H_2O_2]$ increases by $\times 1.5$, rate increases by $\times 1.5$. Therefore 1st order w.r.t $H_2O_2$."
    *   *Example:* "Using Expts 3 and 4: $[H^+]$ changes but rate has no effect. Therefore zero order w.r.t $H^+$."

### Graphs & Half-Lives
*   **Proving 1st Order from a Graph**: The mark scheme demands two components:
    1. Draw construction lines on the graph to find *at least two* consecutive half-lives.
    2. State that the half-lives are constant. *E.g., "Time taken for concentration to halve is constant at 150 s. Evidence seen on graph."*
*   **Initial Rate Determination**: To find the initial rate from a concentration-time graph, you must draw a tangent at $t = 0$ and calculate its gradient: $\frac{\Delta y}{\Delta x}$.

### "Pseudo-Order" Reactions
*   **Question**: *Explain why a large excess of a reactant (e.g. $NH_3$ or water) needs to be used in order to obtain the results.*
*   **Answer**: "So that $[NH_3]$ is effectively constant AND does not affect the rate / reaction behaves as zero order with respect to $NH_3$."
*   *Note on Solvents:* For aqueous hydrolysis reactions (such as acid-catalyzed ester hydrolysis), $\text{H}_2\text{O}$ is in massive excess because it is the solvent. Thus, $[\text{H}_2\text{O}]$ is effectively constant, making the reaction pseudo-first-order overall even though water is a reactant.

### Mechanisms and Equations
*   **Identifying the RDS from equations**: If a rate equation is Rate = $k[NO]^2[H_2]$, and the overall equation is $2NO + 2H_2 \rightarrow N_2 + 2H_2O$. 
    *   The RDS is a step where 2 molecules of NO and 1 molecule of H2 collide. (This is a *termolecular* step, often broken down into two steps in reality, but exam questions will follow the stoichiometry-to-order rule).
*   **Justifying the RDS**: "The reactants in the rate-determining step match the species (and their orders) in the rate equation."
*   **Distinguishing Catalysts from Intermediates**:
    *   *Catalyst*: Consumed in step 1, produced in step 2 (e.g., $Fe^{2+}$).
    *   *Intermediate*: Produced in step 1, consumed in step 2.

### Arrhenius Equation Graphs (Paper 4 Favorites)
*   If you are given a graph of $\ln k$ (y-axis) against $1/T$ (x-axis):
    *   Gradient $m = -\frac{E_a}{R}$.
    *   To calculate $E_a$, find the gradient using points from the line of best fit, multiply by $-R$ ($-8.31 \text{ J K}^{-1} \text{ mol}^{-1}$), and divide by 1000 to get $\text{kJ mol}^{-1}$.
    *   *Mark Scheme Trap*: Don't forget the negative sign! The gradient is negative, so $E_a$ ends up positive. 

### Catalysis Nuances
*   When defining homogeneous vs heterogeneous, always explicitly reference the **states/phases** of the catalyst *relative to the reactants*.
*   For the $S_2O_8^{2-}$ / $I^-$ reaction, the mark scheme accepts the steps occurring in either order (i.e., $Fe^{2+}$ oxidized first, OR $Fe^{3+}$ reduced first). Both are valid because it is a cyclic catalytic process.