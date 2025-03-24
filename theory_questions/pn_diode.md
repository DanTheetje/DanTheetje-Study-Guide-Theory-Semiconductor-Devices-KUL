# Study Questions for p-n Diode

## Chapter III: The p-n Diode

### III.1 Description

- What is the basic structure of a p-n diode?

---

### III.2 The Space Charge Region

#### III.2.1 The Semiconductor in Equilibrium

##### III.2.1.1 The Shockley Approximation

- What happens when an n-type semiconductor is brought in contact with a p-type semiconductor? When is equilibrium reached?
- Draw the band diagram of a pn junction in equilibrium. Explain the structure of the bands.
- What is the space charge region, and why does it form?
- How does the Shockley approximation simplify the analysis of the p-n junction?

##### III.2.1.2 Potentials and Band Bending in Equilibrium

- Draw a diagram with the carrier concentration as a function of the position in the junction. Do the same for the space charge density.
- How do potentials vary across a p-n diode in equilibrium?
- What is the built-in voltage (Vbi), and how is it derived?
- Explain following terms: a one-sided diode, a symmetrical diode and a linearly graded junction

##### III.2.1.3 Carrier Concentrations in Equilibrium

- How are carrier concentrations in a p-n diode SCR determined under equilibrium conditions? 
- Why does this justify the Shockley approximation?

#### III.2.2 The Biased p-n Diode

##### III.2.2.1 Potentials and Band Bending in the Biased p-n Diode

- How does applying a bias voltage affect the band structure of a p-n diode?
- Why is the electrion (hole) quasi fermi level constant in the neutral n(p)-region? What happens at the junction? 
- What is forward bias, which doped side has a higher voltage?
- What happens to the space charge region under forward and reverse bias?

##### III.2.2.2 Carrier Concentrations in the Biased p-n Diode

- How do minority carrier concentrations change with applied bias? What is the effect on the edges of the SCR. On what assumption is this based? How is this relation called?
- What is the effect of the variation of the minority carrier concentration at the edges of the SCR on the majority carrier concentration? Is this effect significant?
- How does the pn product in the SCR differ when a forward bias or a reverse bias is biased on the junction?

---

### III.3 Current Characteristics

#### III.3.1 Drift and Diffusion Currents

##### III.3.1.1 Contribution of Minority Carriers

###### Constant doping levels

- Why is there only diffusion current in the neutral region for constant doping levels?
- What is the diffusion length? Why does it's relation to the neutral region's width matter?
- How does the minority carrier contribution change in short vs. long regions? How does scale with the distance?

###### Non-constant doping levels

- Is there a field now? Why?

- What is the effect of the mobility modulated integrated doping concentrations on the minority carrier current ?

##### III.3.1.2 The Total Drift + Diffusion Current

* How to find the current flowing in steady state if there is the abscence of recombination in the SCR on the biased pn diode?

###### Two short regions, unspecified doping

- Why is the sum of the electron and hole current enough to find the total current flowing in steady state for two short regions? Why isn't this the case for long regions? 
- What is the convention for positive current and its relation to the p or n region?

###### Length of neutral regions not specified, constant doping profiles

* These current formula's can be rewritten the same as the previous current formulas, however the mobility modulated integrated doping concentration changed. Of what is this factor a function now? Compare it to the original mobility modulated integrated doping concentration.

###### Interpretation

* Draw the $Jpn$ as a function of $Vpn$.

* What is the saturated current? When is it reached?

* In forward bias and long regipn, how does the $J_n$ and $J_p$ current contribute together to correspond to a charge +q moving from $W_p$ to $W_n$?

* Is this also true in the short region? Why (not)?

* Now for the reverse bias, what happens with an electron in the p region for a short and for a long neutral region?

##### III.3.1.3 Contribution of Majority Carriers

- Why does the majority carrier concentration adjust itself?
- Why is the majority current only deducable from the minority current?
- Why can’t the Shockley approximation evaluate the drift current of majority carriers? (Because of there actually being a small field in the neutral region that creates non-neglible driftcurrent)

#### III.3.2 High Injection

- When is the forward bias high enough to make the definitions of minority and majority carriers obsolete?
- What is the High Injection region?
- How does high injection affect current-voltage characteristics? draw qualitatively a current voltage plot. 

#### III.3.3 Generation and Recombination Currents

* Why does recombination happen when a forward bias is applied and generation happen when a reverse bias is applied?

##### III.3.3.1 Forward Bias

- What role does recombination play in the forward bias region?
- What three regions can be found in the J-V characteristic for the total forward bias current? Why?

##### III.3.3.2 Reverse Bias

- Why does the reverse current increase with increasing reverse bias?
- By what is the total reverse current given? What term dominates for a large or small bandgap material?

#### III.3.4 Junction Breakdown

##### III.3.4.1 Zener Effect

- What is the Zener breakdown mechanism?
- How big is the field for Zener breakdown to occur? How much volt then can be put on a Si or Ge semiconductor?
- What happens with this voltage if the temperature increases?

##### III.3.4.2 Avalanche Breakdown

- How does impact ionization lead to avalanche breakdown? Explain the physical mechanism.
- When does avalanche breakdown mathematically occur?
- How is breakdown voltage related to doping concentrations and bandgap?
- Why can diodes be made that break down with zero temperature coefficient (no temperature dependence)?

#### III.3.5 Current Characteristics of a p-n Diode

- What is the general shape of the I-V curve for a p-n diode for forward and reverse bias? Explain.
- What is the ideality factor that can be used to represent the current mechanisms in the forward bias?

---

### III.4 The Capacitance of a p-n Diode

#### III.4.1 Junction Capacitance

- What causes junction capacitance in a p-n diode?
- How does junction capacitance depend on bias voltage?

#### III.4.2 Diffusion Capacitance

- How is diffusion capacitance different from junction capacitance?
- How does it affect diode performance?

---

### III.5 Network Models of a p-n Diode and Their Use

#### III.5.1 General Network Model

- What are the key components of a diode’s network model?
- How can this model be used in circuit simulations?

#### III.5.2 Small-Signal Equivalent

- What is the significance of small-signal models for diodes?
- How is the small-signal resistance of a diode determined?

#### III.5.3 Transient Behavior of a Diode

- What factors influence the transient response of a diode?
- How does charge storage affect diode switching times?

---

### III.6 Heterojunction

#### III.6.1 Material Issues

- What materials are commonly used in heterojunctions?
- How do heterojunctions differ from standard p-n junctions?

#### III.6.2 Potentials and Band Bending in a Heterojunction

- How do energy band alignments affect carrier transport in heterojunctions?
- What is the role of band offsets in heterojunction behavior?

#### III.6.3 Current Equations

- How does current flow differ in heterojunctions compared to homojunctions?
- What modifications are needed to traditional diode equations for heterojunctions?

---

### III.7 The p-i-n Diode

#### III.7.1 Description

- What is the structure of a p-i-n diode?
- How does the intrinsic region affect its electrical characteristics?

#### III.7.2 Forward Bias

- How does carrier injection in a p-i-n diode differ from a standard p-n diode?
- Why is the p-i-n diode useful in high-speed and power applications?

ChatGPT & Dante 