# Semiconductor Handbook Questions: The basics

---

---

## Chapter I: Introduction & Semiconductor Properties

### I.1 Scope of the Course

1. What are the primary objectives of this semiconductor course?
2. Why is it important to understand semiconductor device operation before studying solid-state circuits?

### I.2 Semiconductor Crystals

#### I.2.1 Crystal Structure and Orientations

1. What are the main differences between monocrystalline, multicrystalline, polycrystalline, and amorphous semiconductors?
2. How does a unit cell contribute to the overall structure of a crystal?
3. What is the difference between a primitive unit cell and a conventional unit cell.
4. What are Miller indices, and how are they used to describe crystal orientations?
5. Why is the diamond crystal structure significant in semiconductor materials like silicon and germanium?

#### I.2.2 Forbidden Energy Gaps

1. What is the significance of a forbidden energy gap in semiconductors?
2. How does the Pauli exclusion principle relate to energy bands in semiconductors?
3. What distinguishes metals, insulators, and semiconductors in terms of energy band structure?
4. Why does a semiconductor’s conductivity increase with temperature?
5. How does the Fermi level determine whether a material behaves as a conductor, semiconductor, or insulator?

#### I.2.3 Occupation of Allowed States

1. What does the Fermi-Dirac distribution function describe?
2. How does temperature affect the occupation of electron states in a semiconductor?

#### I.2.4 Electrons and Holes

1. What is the role of holes in semiconductor conduction band?
2. Why is it necessary to consider both electron and hole current flow in semiconductor physics?  
3. In which energy band do electron flow and hole flow primarily exist?

#### I.2.5 Dynamics of Electrons and Holes

1. What two forces influence the movement of electrons and holes in a semiconductor? 
2. How does the concept of effective mass come in handy to simplify the dynamics?
3. Why do effective mass values vary for different semiconductors?
4. How do direct and indirect bandgap semiconductors differ in their energy-momentum relationship? Give an example of a direct and indirect bandgap semiconductor.
5. What information is lost in the representation of energy of the band edge as a function of distance comparing to the energy-momentum plot .

#### I.2.6 Energy Density of Allowed States

1. What determines the density of allowed energy states in a semiconductor?
2. How does the number of energy minima in the conduction band (Mc) affect carrier density? What's its relationship to (in)direct bandgap semiconductors?
3. How does the concept of density of states help in understanding carrier concentration? Is the density of states enough information to know this concentration?

#### I.2.7 Densities of Electrons and Holes

1. How is the density of electrons in the conduction band calculated?
2. When can the Maxwell-Boltzmann approximation be used for carrier concentration calculations?
3. Of what is the effective density of states in the conduction band a function?
4. How do n and p relate to eachother for a pure and perfect semiconductor?
5. How does temperature affect the intrinsic carrier concentration?
6. What is the relationship between the intrinsic carrier concentration and the bandgap energy? What does this physically mean?

#### I.2.8 Bond Models in Semiconductors

1. How do covalent bonds contribute to semiconductor conductivity?
2. What is the significance of thermal vibrations for covalent bonds?
3. How does electron-hole pair generation relate to bond breaking?
4. How much minimum energy is required to release an electron (and hole) from a covalent bond.

#### I.2.9 The Doped Semiconductor

1. Why do group III and group V elements act as acceptors and donors, respectively?
2. How does doping affect the position of the Fermi level?
3. Why does doping increase the conductivity of a semiconductor?

---

---

## Chapter II: The Basic Equations

### II.1 The pn-product

#### II.1.1.1 The Intrinsic Semiconductor

1. What is the Fermi-Dirac distribution function, and how does it describe electron occupation probability? 
2. How do the concentrations of electrons and holes in a semiconductor in equilibrium relate to the Fermi level?
3. What is an intrinsic semiconductor and what is the intrinsic Fermi level E<sub>i</sub>.
4. What is the significance of the intrinsic carrier concentration, and how is it derived?
5. How does temperature affect the intrinsic carrier concentration in semiconductors like Si, Ge, and GaAs?

#### II.1.1.2 The Doped Semiconductor

1. How is a doped semiconductor also called? 
2. What is the difference between donor and acceptor atoms, and how do they influence carrier types?
3. What is the difference between $N_A , N_D, N_v, N_c, N_A^-, N_D^+$
4. How is charge neutrality maintained in a doped semiconductor?
5. What is the effect of doping on the Fermi level for a p- or n-type semiconductor?

#### II.1.2 Semiconductor Out of Equilibrium

1. What happens to carrier concentrations when a semiconductor is exposed to external excitation (e.g., light)? How does the semiconductor return to the equilibirum?
2. How does the quasi-Fermi level differ from the equilibrium Fermi level?
3. What condition must be satisfied for a semiconductor to be in steady-state non-equilibrium?
4. How does the product of electron and hole concentrations change in non-equilibrium conditions?

---

### II.2 Carrier recombination and generation mechanisms

#### II.2.1 Generation and Recombination

1. What is the fundamental difference between generation and recombination processes in semiconductors?
2. Under what conditions does net recombination or net generation occur?
3. What role does thermal generation play in maintaining equilibrium carrier concentrations?
4. How does recombination drive a semiconductor back to equilibrium?
5. What is the significance of the minority carrier lifetime in recombination processes?

#### II.2.2.1 Shockley-Read-Hall Generation and Recombination

###### BULK CENTERS

1. What is the physical mechanism behind Shockley-Read-Hall (SRH) recombination?
2. What factors influence the efficiency of SRH recombination?
3. What is the significance of recombination centers in semiconductor devices? On what carrier concentration does if have more effect (majority or minority)?
4. When does the minority carrier rule not apply? Give an example of such a sytem.
5. Which recombination centers are the most efficient?

###### SURFACE AND INTERFACE STATES

1.  How are Tamm surface states created?

2. What are the 2 main differences with the analysis of bulk centers?

3. Only the contribution from the traps around a window of what length around $E_i$ are of importance of the rec/gen rate?

#### II.2.2.2 Radiative Generation and Recombination

1. Explain a radiative recombination process.
2. In what kind of semiconductors is this effect negligible? Why?
3. How does temperature affect radiative recombination efficiency?
4. What carrier concentration is usually not significantly altered by this kind of recombination? What implications does this have on the formula for $R_r$?
5. When and where does radiative generation happen?

#### II.2.2.3 Auger Recombination and Impact Ionization

1. How much particles are involved in this process?
2. What role does doping have on Auger recombination?
3. How does carrier concentration influence Auger recombination efficiency?
4. What is impact ionization, and how does it contribute to carrier generation?
5. In what types of semiconductor devices is impact ionization a critical phenomenon?

#### II.2.2.4 Relative Importance of Different Recombination Mechanisms

1. Describe the relative importance of each contribution for the three different minority carrier lifetimes as a function of the doping level. (Figure II.10)

---

### II.3 Carrier transport

#### II 3.1 Band structure and electric field; the electrostatic potential

1. What is the relation between the coulomb force, electric field and electric potential energy on an electron when a field is applied.

#### II.3.2.1 Drift

###### The drift velocity

1. How do electrons and holes move when in equilibrium? How is this velocity called?
2. How does an electric field influence carrier motion? How is this velocity called?
3. What is mobility? Of what is it a function? 
4. Give 2 important scattering mechanisms in Si.
5. Explain this statement: "The holes have smaller mobility than the electrons."
6. What is saturation drift velocity? When does it happen? Why does it happen? Give approximate values of the saturation drift velocity and at what field it is reached.
7. Why does GaAs staturation velocity decrease at 3000V/cm

###### The drift current

1.  Explain how the drift current formula's are formed.

#### II.3.2.2 Diffusion

1. What is diffusion? Where does it come from?
2. How does the Einstein relation connect diffusion coefficient and mobility? What role does the temperature play in this?
3. What practical applications rely on carrier diffusion in semiconductors?

#### II.3.3 The Current Equations

1. What are the components of the electronic current in semiconductors?
2. For a given semiconductor, what gradient is the driving force behind the current.
3. How can the current equations be linked to force?
4. Why is a semiconductor electrode junction in equilibrium? What does this mean for the quasi fermi level of the electrons and holes in one of the semiconductor materials? 
5. What does the difference between the two fermi levels of the two semiconductor materials on a electrode junction signify?
6. Why is the field in the bulk of an extrinsic semiconductor usually very small?
7. What carriers (majority/minority) have the most effect on diffusion current. Why?
8. How is the mobility-modulated carrier concentration related to current flow?

#### II.3.4 The Continuity Equation

1. What do the continuity equations express? 
2. What is the fundamental origin of a change in carrier concentration in an elementary volume?
3. What simplifications can be made? 

---

### II.4 Poisson Equation

1. How is space charge density related to the electrostatic potential?
2. Why is the equation for space charge density in semiconductors sensical? How does it relate to the charge neutrality: $p + N_D = n + N_A$?
3. How does the space charge density differ between semiconductors and insulators?

---

### II.5 Summary of the Semiconductor Equations

1. What are the ten fundamental semiconductor equations?
2. What arethe physical and time-based boundary conditions necessary for solving semiconductor equations?

----

ChatGPT & Dante