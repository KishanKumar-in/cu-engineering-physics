# ENGINEERING PHYSICS (CONT_26SPH-141)
## Master Examination Definition & Formula Compendium — Units 1, 2 and 3

**Source:** Course repository `KishanKumar-in/cu-engineering-physics` (lecture notes + PPT slide text, Dr. Nandni Sharma, UIE, Chandigarh University, session 2026-27).
**Course Outcomes:** CO1 define fundamentals · CO2 explain working principles · CO3 apply to problems · CO4 compare properties · CO5 analyse suitability for futuristic applications.

---

### EXAMINER'S COVERAGE NOTE (read first)

1. **Equations in the source notes are embedded as images and were lost in text extraction.** Wherever the notes only say "given by [blank]", the formula below is the standard textbook form that the notes' own derivation leads to. They are the same equations the lecturer writes on the board.
2. Items marked **[SYLLABUS – not in uploaded notes]** appear in the official syllabus but have no lecture note or slide in the repository. They are kept short and standard. The repository contains **no** lecture on: Schrödinger equation, quantum tunnelling theory, expectation values, Compton effect, He-Ne laser (named only as a four-level example), Josephson effect, or London equations. Do not rely on this file for those beyond the brief entries given.
3. Where the lecture notes make a statement that differs from the standard textbook, the notes' version is given (that is what the exam is marked against) with a **⚠ Examiner's flag**.
4. Practical (lab) units are excluded; this compendium covers the theory units only.

---

# UNIT 1 — QUANTUM PHYSICS AND NANOTECHNOLOGY

---

### Unit 1 - Chapter 1.1: Quantum Mechanics

#### 1. Complete Glossary of Definitions & Laws

**1.1 Need for Quantum Mechanics (Introduction)**
- **Definition:** Classical (Newtonian) physics fails for systems on the atomic scale; two classic failures are (i) radiation emitted by a heated body (black body spectrum) and (ii) emission of electrons by an illuminated metal. Quantum mechanics (term coined by Max Born, 1924) resolves these.
- **Significance:** Foundation of nanotechnology, condensed matter, quantum chemistry, electronics, quantum computing.
- **Limitation:** Classical laws remain valid for macroscopic bodies.

**1.2 Black Body**
- **Definition:** A hypothetical body that completely absorbs all radiant energy falling on it, reaches an equilibrium temperature and re-emits the energy as fast as it absorbs it.
- **Practical approximation:** A small hole in a hollow cavity; the hole acts as a perfect absorber and the radiation leaving depends only on the cavity wall temperature.
- **Spectrum behaviour:** Intensity rises with wavelength, reaches a maximum, then falls. As T increases, total radiated energy increases and the peak shifts to **shorter** wavelength (up to a few hundred °C mostly infrared; hotter → visible).

**1.3 Planck's Radiation Law (Quantum Hypothesis)** — formulated 1900, Max Planck
- **Postulates (assumptions):**
  1. Walls of the black body contain a large number of electrical oscillators, each vibrating with its own frequency ν.
  2. An oscillator can have only discrete energies, integral multiples of hν: $E_n = nh\nu$ (n = 0, 1, 2, …).
  3. An oscillator emits/absorbs energy only when changing from one allowed level to another; the quantum emitted is $\Delta E = E_1 - E_2 = h\nu$.
- **Law (spectral energy density per unit volume):**
$$u(\nu)\,d\nu=\frac{8\pi h\nu^{3}}{c^{3}}\cdot\frac{1}{e^{h\nu/kT}-1}\,d\nu \qquad\text{or}\qquad E_\lambda\,d\lambda=\frac{8\pi hc}{\lambda^{5}}\cdot\frac{1}{e^{hc/\lambda kT}-1}\,d\lambda$$
  - $h$ = Planck's constant (J·s); $\nu$ = frequency (Hz); $c$ = speed of light (m/s); $k$ = Boltzmann constant (J/K); $T$ = absolute temperature (K); $\lambda=c/\nu$ (m).
- **Significance:** Explained black-body spectrum; resolved the **ultraviolet catastrophe** (classical Rayleigh–Jeans fails at high frequency); started quantum theory.
- **Value (notes):** $h = 6.62606957\times10^{-34}$ J·s.
- **Supplementary (peak shift; notes link to Wien):** $\lambda_{max}T = 2.898\times10^{-3}$ m·K.

**1.4 Photoelectric Effect**
- **Definition:** Emission of electrons (photoelectrons) from a metal surface when light of suitable frequency falls on it; the process is *photoemission*; the current is *photoelectric current*. Discovered by Hallwachs (1887), verified by Hertz; explained by Einstein.
- **Principle:** Law of conservation of energy. Light consists of photons of energy $E=h\nu$; one photon transfers its energy to one electron.
- **Threshold frequency $\nu_{th}$:** minimum frequency that ejects photoelectrons; constant for a metal. $\nu<\nu_{th}$: no emission; $\nu=\nu_{th}$: emission with zero KE; $\nu>\nu_{th}$: emission with KE.
- **Threshold wavelength $\lambda_{th}=c/\nu_{th}$:** greatest wavelength that produces emission. $\lambda<\lambda_{th}$: emission; $\lambda=\lambda_{th}$: zero KE; $\lambda>\lambda_{th}$: none.
- **Work function (threshold energy) $\phi=h\nu_{th}=hc/\lambda_{th}$:** minimum energy needed to remove an electron from the conductor to a point just outside the surface; characteristic of the metal. $E<\phi$ none; $E=\phi$ zero KE; $E>\phi$ emission with KE.
- **Einstein's photoelectric equation:**
$$h\nu = \phi + K_{max}=\phi+\tfrac12 mv_{max}^{2}$$
  - $K_{max}$ = max kinetic energy of ejected electron (J); $m$ = electron mass (kg); $v_{max}$ = max speed (m/s).
- **Significance:** Proves the **particle (photon) nature of light**; classical wave theory cannot explain instantaneous emission and the frequency threshold.
- **Limitation:** KE depends on frequency, **not** intensity; intensity only controls the number of photoelectrons.

**1.5 Heisenberg Uncertainty Principle** (1927)
- **Statement:** It is impossible to determine simultaneously both the position and the momentum of a particle with unlimited accuracy; the product of the uncertainties is at best of the order of $\hbar$ (exact statement: can never be smaller than $\hbar/2$).
- **Origin:** A particle is a **wave packet** moving with group velocity (Born's probability interpretation: particle may be anywhere within the packet). Large packet → momentum well defined but position uncertain; tiny packet → position defined but momentum uncertain.
- **Forms (three forms asked in exams):**
$$\Delta x\,\Delta p\ \ge\ \frac{\hbar}{2},\qquad \Delta E\,\Delta t\ \ge\ \frac{\hbar}{2},\qquad \Delta J\,\Delta\theta\ \ge\ \frac{\hbar}{2},\qquad \hbar=\frac{h}{2\pi}$$
  - $\Delta x$ = position uncertainty (m); $\Delta p$ = momentum uncertainty (kg·m/s); $\Delta E$ = energy uncertainty (J); $\Delta t$ = time uncertainty (s); $\Delta J$ = angular momentum uncertainty (J·s); $\Delta\theta$ = angle uncertainty (rad).
- **Significance:** Holds for all *canonically conjugate* quantities whose product has dimension of action (J·s). A consequence of wave–particle duality, not of instrument defect.
- **Application 1 — Non-existence of electron in the nucleus:** Nuclear radius ≈ $10^{-14}$ m so $(\Delta x)_{max}\approx10^{-14}$ m; $\Delta p\ge\hbar/2\Delta x\approx5.3\times10^{-21}$ kg·m/s; kinetic energy ≈ **97 MeV (notes)**; but the maximum KE of β-electrons observed from the nucleus is **4 MeV**. Hence electrons cannot exist inside the nucleus.
  - ⚠ Examiner's flag: the 97 MeV figure comes from the non-relativistic $p^{2}/2m$; the relativistic estimate is ≈10 MeV. Either way it far exceeds 4 MeV, so the conclusion stands.
- **Application 2 — Existence of proton/neutron in the nucleus:** With $\Delta x\approx10^{-14}$ m the same $\Delta p$ gives KE ≈ 0.05 MeV for a proton (about the same for a neutron), far **smaller** than energies of particles emitted by the nucleus → protons and neutrons can exist inside.

**1.6 de Broglie Hypothesis (Matter Waves)**
- **Statement:** Nature loves symmetry; if radiation (normally a wave) can behave as a particle, then particles (electrons, protons, …) in motion should exhibit wave properties. The associated waves are *matter waves / de Broglie waves / pilot waves*.
- **Wavelength:**
$$\lambda=\frac{h}{p}=\frac{h}{mv}$$
  - Derivation hint: photon $E=h\nu=pc\Rightarrow p=h/\lambda$; extend to $p=mv$.
- **Forms:**
  - Accelerated charged particle ($qV=\tfrac12mv^2$): $\lambda=\dfrac{h}{\sqrt{2mqV}}$; for an electron $\lambda=\dfrac{12.27}{\sqrt V}\text{ \AA}=\dfrac{1.227}{\sqrt V}\text{ nm}$.
  - In terms of kinetic energy K: $\lambda=\dfrac{h}{\sqrt{2mK}}$.
  - Thermal equilibrium ($K=\tfrac32kT$): $\lambda=\dfrac{h}{\sqrt{3mkT}}$.
- **Properties of matter waves (exam list):**
  1. Waves associated with matter in motion, $\lambda=h/p$.
  2. Not progressive waves; they are localized waves.
  3. Not single waves; a group of waves (wave packet) from superposition of progressive waves.
  4. Called pilot waves; represent direction of propagation of the matter.
  5. Unlike EM waves, speed is not constant; depends on particle mass. Independent of charge. $\lambda\propto 1/m,\ 1/v$.
- **Significance:** Basis of wave mechanics, electron microscopy and electron diffraction.
- **Limitation:** For macroscopic bodies $\lambda$ is too small to detect.

**1.7 Wave Packet; Group Velocity; Phase Velocity**
- **Why needed:** Relativity says particle speed $v<c$; a single de Broglie wave has $v_p=c^2/v>c$ (faster than the particle, leaving it behind). Schrödinger resolved this: a moving particle equals a **wave packet** (group of waves of slightly different λ).
- **Group velocity $v_g$:** velocity with which the wave packet (superposition of waves of slightly different wavelengths) travels. $v_g=d\omega/dk$.
- **Phase velocity $v_p$:** velocity with which a point of constant phase of an individual wave travels. $v_p=\omega/k$.
- **Results:**
$$v_p=\frac{\omega}{k}=\frac{E}{p}=\frac{c^{2}}{v},\qquad v_g=\frac{d\omega}{dk}=v,\qquad v_p\,v_g=c^{2},\qquad v_g=v_p-\lambda\frac{dv_p}{d\lambda}$$
  - $\omega=2\pi\nu$ (rad/s); $k=2\pi/\lambda$ (rad/m).
- **Significance:** The velocity of the material particle equals the **group velocity**.

**1.8 Wave Function Ψ**
- **Definition:** The quantity that characterizes the de Broglie (matter) wave; $\Psi=\Psi(x,y,z,t)$; gives complete information about the state of the system (state function / probability amplitude).
- **Physical significance (Born):** $|\Psi|^{2}=\Psi^{*}\Psi$ = **probability density** (probability per unit volume). Probability in $dv=dx\,dy\,dz$ is $|\Psi|^{2}dv$. Ψ itself has no direct physical meaning.
- **Normalization:** $\displaystyle\iiint|\Psi|^{2}\,dx\,dy\,dz=1$ (particle is certainly somewhere).
- **Orthogonality:** two wave functions satisfy $\displaystyle\int\psi_1^{*}\psi_2\,dx=0$.
- **Properties of an acceptable wave function:**
  1. Finite everywhere (avoid infinite probability).
  2. Single-valued (unique probability).
  3. Continuous, and for finite potentials $\partial\Psi/\partial x,\partial\Psi/\partial y,\partial\Psi/\partial z$ also continuous.
  4. $\Psi\to0$ as $x\to\pm\infty$ (so it can be normalized).

**1.9 Quantum Tunnelling [SYLLABUS – not in uploaded notes]**
- **Definition:** A particle of energy $E$ has a non-zero probability of crossing a potential barrier of height $V_0>E$, because $\Psi$ penetrates the barrier (decays exponentially) instead of vanishing.
- **Transmission (thin/wide-barrier estimate):** $T\approx e^{-2\kappa L}$, $\kappa=\sqrt{2m(V_0-E)}/\hbar$; $L$ = barrier width (m).
- **Appears in the notes only as applications:** scanning tunnelling microscope (STM, IBM Zurich 1981); magnetic tunnel junctions (MRAM); nano-transistors show tunnelling and quantised conductance.

#### 2. Formula & Constant Reference Sheet

| Quantity | Relation | Notes |
|---|---|---|
| Photon energy | $E=h\nu=hc/\lambda$ | $hc=12400\text{ eV}\cdot\text{\AA}$ |
| Einstein | $h\nu=\phi+\tfrac12mv_{max}^2$ | $eV_s=K_{max}$ |
| Work function | $\phi=h\nu_{th}=hc/\lambda_{th}$ | eV or J |
| de Broglie | $\lambda=h/mv=h/p$ | |
| Accelerated e⁻ | $\lambda=h/\sqrt{2meV}=12.27/\sqrt V\text{ \AA}$ | V in volts |
| From KE | $\lambda=h/\sqrt{2mK}$ | $\lambda(\text{\AA})=12.27/\sqrt{K(\text{eV})}$ for e⁻ |
| Thermal | $\lambda=h/\sqrt{3mkT}$ | |
| Uncertainty | $\Delta x\Delta p\ge\hbar/2$; $\Delta E\Delta t\ge\hbar/2$ | |
| Phase/group | $v_p=\omega/k=c^2/v$; $v_g=v$; $v_pv_g=c^2$ | |
| Normalization | $\int|\Psi|^2dv=1$ | |

**Constants (as used in the notes):** $h=6.62\times10^{-34}\text{ J}\cdot\text{s}$ (6.63 in some problems) · $\hbar=1.055\times10^{-34}\text{ J}\cdot\text{s}$ · $c=3\times10^{8}\text{ m/s}$ · $k=1.38\times10^{-23}\text{ J/K}$ · $m_e=9.1\times10^{-31}\text{ kg}$ · $e=1.6\times10^{-19}\text{ C}$ · $m_n=1.676\times10^{-27}\text{ kg}$ · $m_p=1.673\times10^{-27}\text{ kg}$ · $1\text{ eV} = 1.6\times10^{-19}\text{ J}$ · $1\text{ \AA} = 10^{-10}\text{ m}$.

**Worked numericals from the notes (answers computed):**
| Problem | Answer |
|---|---|
| e⁻ of 2000 eV | $\lambda=12.27/\sqrt{2000}\approx0.274\text{ \AA} = 2.74\times10^{-11}\text{ m}$ |
| e⁻ with $\lambda = 1.66\times10^{-10}\text{ m}$ | $v=h/m\lambda\approx4.4\times10^{6}\text{ m/s}$; $K\approx8.8\times10^{-18}\text{ J} \approx 55\text{ eV}$ |
| e⁻ under 15 kV | $\lambda\approx0.100\text{ \AA} = 1.0\times10^{-11}\text{ m}$ |
| Neutron, $K=2m_ec^2$ (interpreting the notes' wording) | $\lambda=h/\sqrt{2m_nK}\approx2.8\times10^{-14}\text{ m}$ |
| e⁻ under 1600 V | $\lambda\approx0.307\text{ \AA}$ |
| e⁻ under 100 V (practice) | $\lambda\approx1.227\text{ \AA}$ |

#### 3. Top 5 Most Repeated Exam Questions & Derivation Outlines

**Q1. State and explain Planck's assumptions / Planck's radiation law. What is a black body?** (listed as practice question)
1. Define black body + cavity-hole model. 2. Write the three postulates (oscillators, $E=nh\nu$, emission $\Delta E=h\nu$). 3. Write the law with symbols. 4. State success: UV catastrophe resolved. 5. Sketch intensity vs λ for two temperatures (peak shifts to shorter λ as T rises).

**Q2. Explain the photoelectric effect; derive Einstein's equation; define threshold frequency, wavelength, work function.**
1. Define effect + photoelectron. 2. One photon → one electron. 3. Energy conservation: $h\nu=\phi+K_{max}$. 4. Three cases for $\nu$ vs $\nu_{th}$ (and E vs φ, λ vs $\lambda_{th}$). 5. Conclude: particle nature of light; KE independent of intensity.

**Q3. State Heisenberg's uncertainty principle; write its three forms; prove electrons cannot exist in the nucleus.**
1. Wave-packet argument for uncertainty. 2. Statement and three forms. 3. Set $\Delta x=10^{-14}\text{ m} \to \Delta p\ge\hbar/2\Delta x$. 4. $K=p^2/2m\approx97\text{ MeV}$ (notes) vs observed 4 MeV → electron cannot exist. 5. Repeat for proton → KE ≪ emitted energies → can exist.

**Q4. State the de Broglie hypothesis; derive $\lambda$ for an accelerated electron; list properties of matter waves; numericals (2000 eV, 100 V, 15 kV, 1600 V, 1.66 Å).**
1. Symmetry argument; $\lambda=h/p$. 2. $qV=\tfrac12mv^2\Rightarrow p=\sqrt{2mqV}$. 3. $\lambda=h/\sqrt{2meV}=12.27/\sqrt V\text{ \AA}$. 4. Properties (five points). 5. Substitute numbers carefully in SI, convert eV→J.

**Q5. Define phase and group velocity; prove the velocity of the material particle equals the group velocity; relate them. Also: acceptable wave-function properties; normalized and orthogonal functions.**
1. $v_p=\omega/k$, $v_g=d\omega/dk$. 2. $E=\hbar\omega$, $p=\hbar k$. 3. $E=p^2/2m\Rightarrow v_g=dE/dp=p/m=v$. 4. $v_p=E/p=c^2/v$ ⇒ $v_pv_g=c^2$; $v_g=v_p-\lambda\,dv_p/d\lambda$. 5. For the wave-function part: Born interpretation, four properties, normalization integral, orthogonality integral.

---

### Unit 1 - Chapter 1.2: Nanotechnology

#### 1. Complete Glossary of Definitions & Laws

**1.1 Nanotechnology / Nanomaterials**
- **Definition:** Field of research and innovation concerned with designing, building, manipulating and applying materials and devices at the scale of atoms and molecules (nanoscale); special properties arise from **quantum effects** and a **high surface-area-to-volume ratio**.
- **Nanomaterials size:** typically 0.1–100 nm (lecture notes) / 1–100 nm (slides). $1\text{ nm} = 10^{-9}\text{ m} = \text{ten times the diameter of a hydrogen atom}$; a human hair ≈ 80,000 nm.
- **Significance:** Colour, strength, conductivity and reactivity differ substantially between nanoscale and bulk.
- ⚠ Examiner's flag: notes say 0.1–100 nm, slides say 1–100 nm; quote **1–100 nm** as the standard definition and mention 0.1 nm as the lower bound if the question asks "notes' range".

**1.2 History (dates are directly examinable)**
| Year | Event |
|---|---|
| 1959 (29 Dec) | Richard Feynman's lecture (APS meeting, Caltech) — idea of building at atomic scale |
| 1974 | Norio Taniguchi first defined the term "nanotechnology" |
| 1981 | IBM Zurich built the **scanning tunnelling microscope (STM)** — sees single atoms |
| 1985 | Discovery of C₆₀ **buckminsterfullerene** (buckyball), soccer-ball shaped |
| 1990 | IBM moved 35 xenon atoms on nickel with an STM to spell "IBM" |
| 1991 | **Carbon nanotubes** created: ~6× lighter, ~100× stronger than steel |
| 2014 / 2015 / 2016 | Intel 14 nm transistor / IBM 7 nm transistor / Lawrence Berkeley Lab 1 nm transistor (typical transistor at the turn of the century: 130–250 nm) |

**1.3 Applications of nanotechnology (as listed in the notes)**
- **Materials:** ballistic body armour, wrinkle/stain/bacteria-resistant fabrics, smart fabrics; clear nano-films (water-repellent, antireflective, self-cleaning, UV/IR resistant, antifog, antimicrobial, scratch-resistant, conductive); nanostructured ceramic coatings; lubricants; nano-catalysis (petroleum refining, catalytic converters).
- **Electronics / IT:** smaller transistors; **MRAM** (magnetic tunnel junctions → instant boot); **quantum-dot** displays.
- **Medicine:** HDL-mimic nanoparticles for atherosclerosis; targeted cancer drug delivery; regenerative medicine (bone, neural; graphene nanoribbons for spinal cord repair); needle-free vaccines, universal flu vaccine scaffold.
- **Energy:** better catalysis, CNT CO₂ scrubbers/membranes, faster-charging batteries, CNT-epoxy windmill blades, nano-valves/sensors in oil and gas.
- **Environment:** MoS₂ nanopore desalination membrane (2–5× more water filtered); nanoparticles to clean groundwater pollutants.
- **Transportation:** structural-health sensors, lightweight materials — 20% less aircraft weight ⇒ up to 15% less fuel; NASA estimate: advanced nanomaterials with twice the strength ⇒ launch vehicle gross weight reduced by up to 63%.

**1.4 Surface-to-Volume Ratio**
- **Principle:** For a sphere of radius $r$: $\dfrac{S}{V}=\dfrac{4\pi r^{2}}{\tfrac43\pi r^{3}}=\dfrac{3}{r}$. Ratio rises as size falls ⇒ more atoms at the surface.
- **Data (notes):** 3 nm particle → 50% of atoms on surface; 10 nm → 20%; 30 nm → 5%.
- **Significance:** Increased reactivity, catalytic efficiency and surface energy.

**1.5 Quantum (Electron) Confinement**
- **Definition:** When a dimension of the particle becomes comparable to the de Broglie wavelength / mean free path of electrons (equivalently the exciton Bohr radius), energy levels change from continuous bands to **discrete levels**; electrons and holes are "squeezed".
- **Chain:** isolated atoms (discrete levels) → solid (bands) → **nanoparticle = intermediate stage**. Smaller size ⇒ larger band gap (blue shift).
- **Effect:** alters electrical, magnetic, optical properties; discrete (finite) density of states in nanocrystals.
- **Analogy:** particle-in-a-box with box size of order of $\lambda_{dB}$.

**1.6 Classification by dimensional confinement**
| Type | Dimensions confined | Free dimensions | Example (notes) |
|---|---|---|---|
| **Quantum well** (2D nanomaterial) | 1 | 2 | Thin films; discrete values → "energy sub-bands" when thickness ≈ $\lambda_{dB}$ |
| **Quantum wire** (1D) | 2 | 1 | Carbon nanotubes |
| **Quantum dot** (0D) | 3 | 0 | Fullerenes, nanoparticles |

**1.7 Unusual Properties of Nanomaterials**
- **Inverse Hall–Petch effect:** Normally hardness/strength rises as grain size falls (grain boundaries block dislocation pile-up). Below ≈15 nm grains cannot support a pile-up, the trend breaks; below ≈5 nm strength can **decrease** with falling grain size.
- **Giant magnetoresistance (GMR):** Dramatic drop in electrical resistance on applying a magnetic field in a hybrid of non-magnetic nano-film between ferromagnetic layers. With no field the layers are anti-ferromagnetically coupled (high resistance); field aligns spins in parallel (low resistance). Used in **spin valves** (micro-switches; spin-valve transistors detect magnetic fields).
- **Superparamagnetism:** Ferromagnetic particle < ≈20 nm becomes a single domain; < ≈5 nm spins are thermally disordered with no field (paramagnetic) but align fully with a field → large magnetisation, no hysteresis.
- **Super-hydrophobicity:** Nano-scale roughness reduces actual contact area; contact angle > 165° (normal best ≈ 120°). Achieved via **Cassie–Baxter** state (droplet rests on asperity tips). Uses: non-wetting clothes, self-cleaning windows, anti-bio-fouling surfaces.
- **Super surface activity:** Surface atoms with unsatisfied bonds give high surface energy ⇒ adsorption of toxic gases, catalysis.
- **Rapid catalysis:** (i) larger surface area, (ii) high surface energy/instability ⇒ activity enhanced by orders of magnitude.
- **Functionalization:** Adding functional groups to a surface (usually by chemical synthesis) to alter affinity or make it water repellent; easier for nanoparticles.
- **Targeted drug delivery:** Nanoparticle loaded with sensor + drug; functionalized surface detects affected tissue and releases the drug locally.
- **Others (one-liners):** nano-porous membrane filters (bacteria-free water); non-wetting clothing; scratch-resistant lenses (nano-alumina ceramics via thermal spraying/spark plasma sintering).

**1.8 Synthesis of Nanomaterials**
- **Top-down approach:** size reduction of bulk material by crushing, milling, grinding (also lithography, laser ablation). *Drawbacks:* non-uniform shapes, high energy for small particles, surface imperfection, crystallographic damage.
- **Bottom-up approach:** build atom-by-atom, molecule-by-molecule or cluster-by-cluster; chemical synthesis; uniform size, shape and distribution; reaction controlled to stop growth.
- **Sol–gel method (bottom-up, chemical):**
  1. Precursors (inorganic metal salts or **metal alkoxides**) undergo **hydrolysis and polymerization (condensation)** → colloidal suspension (**sol**).
  2. Gelation → **gel** (wet).
  3. **Aging** in mother liquor (gel keeps hydrolysing/condensing); includes **syneresis** (expulsion of solvent by shrinkage) and **coarsening** (dissolution–reprecipitation).
  4. Washing, **drying** to remove solvent, then heating.
  - *Sol–gel parameters:* precursor type, solvent, water content, acid/base content, precursor concentration, temperature, aging time.
  - *Advantages:* high purity, molecular-level mixing, homogeneity, low processing temperature, tunable pore size/volume, multi-component in one step, many forms (monoliths, films, fibres, powders), dopant introduction.

**1.9 Quantum Computing (slides)**
- **Definition:** Computing that uses quantum-mechanical principles — **superposition** and **entanglement** — to perform computation. **Qubit:** can be 0, 1 or a superposition of both.
- **Entanglement:** correlated qubit states regardless of separation.
- **Facts:** IBM Eagle 127-qubit processor (2021); nanostructures enable qubit stability; qubits from quantum dots or Josephson junctions.
- **Importance (syllabus):** backbone of next-generation computing.

**1.10 Edge Computing (slides)**
- **Definition:** Computation and data storage placed close to the data source. **Advantages:** low latency, real-time processing, better privacy and efficiency. **Challenges:** infrastructure cost, data security, technical complexity.
- **IoT:** network of interconnected physical devices with sensors and software exchanging data over the internet.
- **Applications:** driverless cars (Tesla Autopilot processes sensor data on-board), healthcare (wearable ECG, ICU monitoring, smart thermometers in COVID-19), driverless contactless delivery, AI thermal imaging.

#### 2. Formula & Constant Reference Sheet
| Item | Relation / Value |
|---|---|
| S/V of sphere | $3/r$ |
| Sphere surface, volume | $4\pi r^2$, $\tfrac43\pi r^3$ |
| Scale | 1 nm = $10^{-9}\text{ m}$; 1 Å = 0.1 nm |
| Superparamagnetic size | < ≈20 nm single domain; < ≈5 nm thermal disorder |
| Inverse Hall–Petch | grain < ≈15 nm (reverses < ≈5 nm) |
| Super-hydrophobic angle | > 165° (normal max ≈ 120°) |
| Surface atoms | 3 nm: 50%; 10 nm: 20%; 30 nm: 5% |

#### 3. Top 5 Most Repeated Exam Questions & Derivation Outlines
**Q1. Define nanomaterials; compare size with other objects; applications in transportation/energy.** — Define; give 1–100 nm; compare (H atom, DNA, hair 80,000 nm, red blood cell); list applications by sector with the 20%/15% and 63% weight-saving figures.

**Q2. What is quantum confinement? How does it affect properties? Classify nanomaterials by confinement (well/wire/dot).** — Atoms → discrete; solids → bands; nano → intermediate; size ≈ $\lambda_{dB}$ ⇒ discrete levels; band gap increases as size decreases; table of 2D/1D/0D with examples.

**Q3. Show that surface-to-volume ratio increases as size decreases.** — $S=4\pi r^2$, $V=\tfrac43\pi r^3$, $S/V=3/r$; give 3/10/30 nm surface-atom percentages; consequences (reactivity, catalysis, melting-point changes).

**Q4. Explain the sol–gel process / define bottom-up approach.** — Top-down vs bottom-up comparison; stages (sol → gel → aging → drying); parameters; advantages (list six).

**Q5. Write short notes on unusual properties: inverse Hall–Petch, GMR/spin valve, superparamagnetism, super-hydrophobicity, targeted drug delivery.** — One definition + one size/number + one application each (use the figures above).

---

### Unit 1 - Chapter 1.3: Nanodevices, Nanocomposites, Sensors and Nano-applications

#### 1. Complete Glossary of Definitions & Laws

**1.1 Carbon Nanomaterials**
- **Definition:** Nanostructured materials made primarily of carbon atoms with unique mechanical, electrical, thermal and chemical properties.
- **Members:** **Graphene** (2D, hexagonal lattice, single-atom-thick sheet), **carbon nanotubes** (CNTs: single-walled SWCNT and multi-walled MWCNT; can be metallic or semiconducting depending on structure; high aspect ratio), **fullerenes** (C₆₀, 0D), **carbon black**, **carbon dots** (nm-sized fluorescent carbon particles).
- **Properties:** excellent conductivity, high strength, barrier properties, surface can be functionalized.

**1.2 Carbon-based Nano-additives**
- **Definition:** Carbon nanomaterials (graphene, CNTs, fullerenes, carbon black) added in small quantity (typically < 5%) to polymers, metals or ceramics to enhance mechanical, electrical, thermal or chemical properties.
- **Benefits:** tensile strength/stiffness/durability; conductive and antistatic composites; heat dissipation; reduced gas and moisture permeability (packaging); reduced wear/friction (lubricants, coatings).
- **Applications:** Li-ion/Na-ion battery electrodes; CNT fillers for EMI shielding; carbon black in touchscreens and conductive inks; carbon-fibre composites in aerospace; CNTs in 3D-printing filaments (ESD protection); fullerene/carbon-dot drug delivery and imaging; flexible electronics, gas/temperature/bio sensors, water purification and air filtration.

**1.3 Green Nanotechnology**
- **Definition:** Use of nanotechnology and **green (biological, plant-extract) synthesis** to create environment-friendly products and processes and to remediate pollution.
- **Principles/aims:** sustainable manufacturing; bioremediation and bio-transformation of soil, wastewater, oil spills and toxic pollutants; waste management and recycling; renewable energy (solar cells, batteries, supercapacitors); sustainable agriculture and food packaging (shelf life, safety).

**1.4 Nanocomposites**
- **Definition:** Materials consisting of a **matrix** (bulk) reinforced with nano-scale fillers having at least one dimension < 100 nm, to improve mechanical, thermal, electrical, barrier or other properties.
- **Types by matrix:** polymer (e.g., epoxy + silica; clay increases tensile strength ≈30%), metal-matrix (e.g., AlSi10Mg/CNT), ceramic-matrix (e.g., zirconia in silica).
- **Uses:** *Coatings* (SiO₂, TiO₂ UV resistance — ≈40% longer life; corrosion resistance; antimicrobial silver); *additives* (antistatic, EMI shielding, heat dissipation, packaging barrier, tensile strength of epoxy with CNTs up to ≈150%); *catalysts* (more active sites, easy separation, heterogeneous catalysts); *structural components* (bumpers, dashboards, aerospace).

**1.5 Semiconductor Nanodevices**
- **Definition:** Electronic devices (< 100 nm) using semiconductors (Si, GaAs, …) whose behaviour is governed by quantum confinement and surface effects. Benefits: faster switching, lower power, very dense integration (Moore's law).
- **Basics:** band gap controls conductivity; doping gives n-type/p-type; confinement gives discrete levels.
- **Nanomanipulators:** precision systems that position/move objects at 1–100 nm (microscopic "robotic arms"): AFM-based, STM-based (e.g., IBM quantum corrals), SEM/TEM-integrated, MEMS-based. Used for DNA/protein/cell handling, mechanical tests on nanotubes, circuit editing.
- **Nano-transistor:** a switch that controls current; channel a few nanometres wide; shows **quantum tunnelling and quantised conductance**; types: FinFET (3D fin), gate-all-around (channel surrounded by gate), CNT/graphene/MoS₂ FETs, flexible transistors on plastic/fabric.
- **Other devices:** quantum-dot qubits, spintronics, nano-LEDs, nano-FET biosensors (glucose, cancer markers).

**1.6 Nanosensors**
- **Definition:** Miniature devices (1–100 nm) that detect and measure physical, chemical or biological changes (pressure, temperature, chemicals, biomarkers) with high sensitivity.
- **Why sensitive:** small size, **high surface area**, tiny sample volumes.
- **Applications:** food safety (E. coli, Salmonella, pesticide residue, smart packaging); water (lead, arsenic, bacteria); air (CO, NO₂, particulates); medical (biomarkers, glucose); industry, agriculture, structural monitoring; contamination detection; wireless/IoT networks.
- **Challenges:** energy efficiency, limited bandwidth, managing huge sensor networks.

**1.7 Nanoencapsulation for Theragnosis and Immunisation**
- **Nanoencapsulation:** enclosing a bioactive **core** (drug, nutrient, antigen) within a nano-scale **shell/carrier** to improve stability, bioavailability, targeting and reduce side-effects.
- **Methods:** emulsion (nano-emulsions 10–200 nm), polymerization, sol–gel, **liposomes** (vesicles like cell membranes carrying hydrophilic and hydrophobic molecules), **electrospraying** (electric field breaks solution into charged droplets → nanoparticles), **cyclodextrin** inclusion complexes (doughnut-shaped cyclic oligosaccharides protecting hydrophobic molecules from heat, light, oxidation).
- **Theragnosis (theranostics):** integration of therapy and diagnosis in one nano-platform: targeted chemotherapy, controlled sustained release, imaging agents for real-time tumour monitoring (MRI, CT).
- **Immunisation:** antigens encapsulated in polymer/lipid/inorganic NPs → better stability, slow release (fewer boosters), longer shelf life, targeting of immune cells, multi-component vaccines.

**1.8 Nanomaterials for Water Treatment**
- **Mechanisms:** **adsorption** (heavy metals, dyes, organics — high surface area, porosity), **photocatalysis** (light → hydroxyl radicals → pollutants broken into CO₂ and H₂O; e.g., TiO₂), **antimicrobial action** (membrane destruction, reactive oxygen species; Ag, ZnO), **membranes/nanofiltration** (graphene-oxide, nanocomposite membranes for desalination and dye removal), **magnetic nanoparticles** (easy regeneration by magnetic separation), ion exchange/redox reactions.
- **Advantages:** safer, longer-lasting alternative to chlorine; rapid; reusable.

**1.9 Nanotechnology for Energy Harvesting**
- **Li-ion battery (working):** electrolyte = lithium salt in solvent; porous separator keeps electrodes apart. Charging: Li⁺ **intercalate** into graphite anode; discharging: Li⁺ move back to cathode while electrons flow through the external circuit. Nano-electrodes give greater surface area and conductivity.
- **Solar cell:** converts sunlight directly into electricity by the **photovoltaic effect**; photons free electrons in the semiconductor (usually Si). Nano-enhancement: quantum dots (tunable absorption, multiple electron–hole pairs per photon), nanowires, thin flexible lightweight cells, better charge collection, reduced recombination, perovskite cells with nano electron-transport layers.
- **Self-powered devices:** harvesting motion, heat, sound (piezoelectric/thermoelectric nanostructures), wearable and implantable devices.

#### 2. Formula & Constant Reference Sheet
| Item | Value |
|---|---|
| Carbon additive loading | typically < 5% |
| Nano-emulsion droplet size | 10–200 nm |
| Superhydrophobic contact angle | > 165° |
| Nanocomposite filler dimension | at least one dimension < 100 nm |
| Reported enhancements (slides) | CNT epoxy up to ≈150% tensile gain; clay ≈30%; TiO₂ coating life ≈40%; corrosion resistance ≈90% better |
| Transistor milestones | 14 nm (2014), 7 nm (2015), 1 nm (2016) |

#### 3. Top 5 Most Repeated Exam Questions & Derivation Outlines
**Q1. Carbon nanomaterials: CNT, graphene, fullerene — structure, properties, applications; carbon-based nano-additives.** — Give dimension class (2D/1D/0D), property list, application list.

**Q2. Nanocomposites for coatings, additives, catalysts and structural components.** — Matrix + filler definition; three matrix types; one example and one quantified benefit each.

**Q3. Nanomanipulators and nano-transistors.** — Definition; four manipulator types; transistor types (FinFET, GAA, CNT-FET); tunnelling and quantised conductance; applications.

**Q4. Nano-sensors for contamination detection / nanoencapsulation for drug delivery and theragnosis.** — Principle (surface area → sensitivity); domains (food, water, air); encapsulation methods (liposomes, emulsions, electrospraying, cyclodextrin); core–shell language.

**Q5. Nanomaterials for water treatment and for energy harvesting (Li-ion battery working, solar cell).** — Four water-treatment mechanisms; intercalation steps; photovoltaic effect and quantum-dot enhancement.

---

# UNIT 2 — SOLID STATE PHYSICS AND ADVANCED MATERIALS

---

### Unit 2 - Chapter 2.1: Crystal Structure

#### 1. Complete Glossary of Definitions & Laws

**1.1 States of Matter**
- **Solid:** atomic positions fixed relative to each other by cohesion/bonds; retains shape; generally denser than liquids. **Liquid:** molecules attract enough to stay in contact but not hold a structure; flows; takes container shape. **Gas:** bonds too weak to hold molecules together; independent molecules interacting by collisions; least dense. **Plasma:** gas with so much energy that electrons cannot stay in orbit — mixture of ions and free electrons; good conductor; most common state in the universe (stars, lightning).
- Phase changes are usually reversible; gas → solid directly is **deposition**.

**1.2 Crystallography**
- **Definition:** Branch of science dealing with the arrangement and bonding of atoms in crystalline solids and the geometric structure of crystal lattices; modern crystallography relies on **X-ray diffraction** by crystals acting as gratings.

**1.3 Crystalline vs Amorphous Solids (tabulate in exam)**
| Crystalline solid | Amorphous solid |
|---|---|
| Regular arrangement | No regular arrangement |
| True solids | Pseudo solids |
| **Anisotropic** | **Isotropic** |
| More rigid | Less rigid |
| Symmetrical | Asymmetrical |
| **Long-range order** | **Short-range order** |
| Diamond, NaCl, metals | Glass, plastic, quartz glass |

**1.4 Space lattice, Basis, Crystal structure**
- **Lattice (space lattice):** hypothetical regular, periodic arrangement of points in space used to describe the crystal. **Lattice point/site:** each point.
- **Basis (motif):** collection of atoms in a fixed arrangement attached to every lattice point (can be one atom or hundreds); the motif lists atoms with their fractional coordinates.
- **Crystal structure = Lattice + Basis.**
- **Unit cell:** smallest repeating unit which, repeated over and over, generates the space lattice.
- **Primitive cell (P):** lattice points only at the corners (e.g., simple cubic). **Non-primitive cell:** extra points elsewhere (BCC, FCC).

**1.5 Lattice Parameters**
- Six values defining a unit cell: edge lengths **a, b, c** and interaxial angles **α (between b and c), β (between a and c), γ (between a and b)**.
- Importance: define geometry and periodicity; determine density, thermal expansion, mechanical behaviour; vary with temperature, composition, pressure.

**1.6 Crystal Systems and Bravais Lattices** (named after Auguste Bravais, 1848; 7 systems, **14** lattices)
| System | Edges | Angles | Bravais lattices | No. |
|---|---|---|---|---|
| Cubic | a = b = c | α = β = γ = 90° | SC (P), BCC (I), FCC (F) | 3 |
| Tetragonal | a = b ≠ c | 90° | P, I | 2 |
| Orthorhombic | a ≠ b ≠ c | 90° | P, C, I, F | 4 |
| Monoclinic | a ≠ b ≠ c | α = γ = 90° ≠ β | P, C | 2 |
| Triclinic | a ≠ b ≠ c | α ≠ β ≠ γ ≠ 90° | P | 1 |
| Trigonal (Rhombohedral) | a = b = c | α = β = γ ≠ 90° | R | 1 |
| Hexagonal | a = b ≠ c | α = β = 90°, γ = 120° | P | 1 |
| **Total** | | | | **14** |

**1.7 Coordination Number (CN)**
- **Definition:** Number of nearest-neighbour atoms in direct contact with an atom. **SC = 6** (weak, unstable), **BCC = 8**, **FCC = 12** (also HCP = 12, close-packed).

**1.8 Effective Number of Atoms per Unit Cell**
- Corner atom shared by 8 cells → 1/8; face-centre atom shared by 2 cells → 1/2; body-centre atom → 1 (not shared).
- **SC:** $8\times\tfrac18=1$. **BCC:** $8\times\tfrac18+1=2$. **FCC:** $8\times\tfrac18+6\times\tfrac12=4$.

**1.9 Atomic Packing Factor (APF)**
- **Definition:** Ratio of the volume of the atoms in one unit cell to the volume of the unit cell itself.
$$\text{APF}=\frac{Z\cdot\tfrac43\pi r^{3}}{a^{3}}$$
  - $Z$ = effective atoms per cell; $r$ = atomic radius (m); $a$ = cube edge (m).
- **Derivations:**
  - **SC:** atoms touch along edge ⇒ $a=2r$; $\text{APF}=\dfrac{\tfrac43\pi r^3}{8r^3}=\dfrac{\pi}{6}=0.524\ (52.4\%)$.
  - **BCC:** atoms touch along body diagonal ⇒ $\sqrt3\,a=4r$, $a=4r/\sqrt3$; $\text{APF}=\dfrac{2\cdot\tfrac43\pi r^3}{(4r/\sqrt3)^3}=\dfrac{\sqrt3\,\pi}{8}=0.68\ (68\%)$.
  - **FCC:** atoms touch along face diagonal ⇒ $\sqrt2\,a=4r$, $a=4r/\sqrt2=2\sqrt2\,r$; $\text{APF}=\dfrac{4\cdot\tfrac43\pi r^3}{(4r/\sqrt2)^3}=\dfrac{\pi}{3\sqrt2}=0.74\ (74\%)$.
- **Significance:** FCC/HCP are close-packed (74%); SC is least dense (52.4%).

**1.10 Miller Indices**
- **Definition:** Set of three integers (hkl) that specify the orientation of a plane (or a set of parallel planes) in a crystal.
- **Procedure:** (1) find intercepts on the axes in units of a, b, c; (2) take reciprocals; (3) clear fractions (multiply by LCM); (4) reduce to lowest integers. Example: intercepts 2, 1, 3 → reciprocals ½, 1, ⅓ → ×6 → **(3 6 2)**.
- **Rules:** plane parallel to an axis has intercept ∞ → index 0; negative intercept written with a bar above the number; number of indices equals dimension.
- **Notation:** (hkl) a plane · {hkl} a family of planes · [hkl] a direction · ⟨hkl⟩ a family of directions · (h,k,l) with commas = a point.
- **Importance:** planes influence optical properties, reactivity, surface tension, dislocations.

**1.11 Interplanar spacing (d-spacing)**
- **Definition:** Distance between adjacent parallel planes of atoms that give diffraction peaks.
$$d_{hkl}=\frac{a}{\sqrt{h^{2}+k^{2}+l^{2}}}\qquad\text{(cubic)}$$
  - $a$ = lattice constant (m); $h,k,l$ = Miller indices.

**1.12 Bragg's Law**
- **Statement:** When X-rays of wavelength λ fall on a crystal at glancing angle θ, constructive interference (strong reflection) occurs when the path difference equals an integral multiple of λ.
$$n\lambda=2d\sin\theta$$
  - $n$ = order of reflection (1, 2, 3…); $\lambda$ = X-ray wavelength (m); $d$ = interplanar spacing (m); $\theta$ = glancing angle between beam and plane (rad/deg).
- **Derivation (as in notes):** Two parallel rays reflect from adjacent planes; extra path = AB + BC; with AB = BC = $d\sin\theta$, path difference $=2d\sin\theta$; for reinforcement path difference $=n\lambda$.
- **Limitation:** requires $\lambda\le2d$ (since $\sin\theta\le1$); only for specific angles; used in crystal-structure determination.

#### 2. Formula & Constant Reference Sheet
| Quantity | SC | BCC | FCC |
|---|---|---|---|
| Atoms per cell Z | 1 | 2 | 4 |
| Coordination number | 6 | 8 | 12 |
| Contact direction | edge | body diagonal | face diagonal |
| Radius–edge relation | $a=2r$ | $a=4r/\sqrt3$ | $a=2\sqrt2\,r$ |
| APF | $\pi/6=0.524$ | $\sqrt3\pi/8=0.68$ | $\pi/3\sqrt2=0.74$ |
| Void fraction | 0.476 | 0.32 | 0.26 |

Other relations: $d_{hkl}=a/\sqrt{h^2+k^2+l^2}$ · $n\lambda=2d\sin\theta$ · density $\rho=\dfrac{Z\,M}{N_A\,a^3}$ ($M$ molar mass kg/mol; $N_A=6.022\times10^{23}\text{ mol}^{-1}$) · $\sin\theta_{max}\le1\Rightarrow n_{max}\le 2d/\lambda$.

#### 3. Top 5 Most Repeated Exam Questions & Derivation Outlines
**Q1. Differentiate crystalline and amorphous solids; define lattice, basis, unit cell, motif; state crystal structure = lattice + basis.** — Table of seven contrasts; definitions with a 2-D sketch.

**Q2. List the 7 crystal systems and 14 Bravais lattices with lattice parameters.** — Reproduce the table above; mark P/I/F/C/R.

**Q3. Define coordination number and effective atoms; derive APF of SC, BCC, FCC.** — Count shared atoms; contact condition (edge/body/face diagonal); express $a$ in $r$; ratio of volumes; final 52.4%, 68%, 74%.

**Q4. What are Miller indices? Explain how to find them; find indices for intercepts (2,1,3); derive $d_{hkl}$.** — 4-step method; worked example giving (362); plane geometry gives $d=a/\sqrt{h^2+k^2+l^2}$; notation summary.

**Q5. State and derive Bragg's law.** — Diagram of two parallel rays; path difference AB+BC; $AB=d\sin\theta$; $n\lambda=2d\sin\theta$; conditions and use.

---

### Unit 2 - Chapter 2.2: Superconductivity

#### 1. Complete Glossary of Definitions & Laws

**1.1 Superconductivity / Superconductor**
- **Definition:** Phenomenon in which certain materials, when cooled below a characteristic **critical temperature**, show **exactly zero electrical resistance** and **expulsion of magnetic field**.
- **History:** Discovered 8 April 1911 by H. Kamerlingh Onnes (Leiden) in **mercury at 4.2 K** (after liquefying helium). First workable theory: **BCS theory (1957), Bardeen–Cooper–Schrieffer**. 1986: ceramic with $T_c=35\text{ K}$; early 1988: Tl–Ca–Ba–Cu–O with $T_c=125\text{ K}$. Highest conventional $T_c$: **MgB₂ at 39 K**. YBaCuO is a standard high-$T_c$ ceramic.
- **Significance:** No $I^2R$ heat loss; persistent currents in a loop (lifetime ≥ 100,000 years experimentally).
- **Resistivity behaviour:** Normal metal: resistance decreases gradually and saturates at a residual value (impurities/defects) even at 0 K. Superconductor: resistance **drops abruptly to zero** at $T_c$ (phase transition).

**1.2 Critical Temperature $T_c$**
- **Definition:** Temperature at and below which resistivity becomes zero and the material transitions from normal to superconducting state. Varies from material to material.
- **High-temperature superconductors:** $T_c$ above ≈125 K (notes: "verifiable Tc > 125 K"), above **77 K = boiling point of liquid nitrogen**, which is cheap and easy compared with liquid helium (4 K).
- **Other signs of the phase transition:** electronic heat capacity shows a discontinuous jump at $T_c$ and stops being linear in T.

**1.3 Critical Magnetic Field**
- **Definition:** $H_c$ (or $B_c$) = minimum magnetic field required to destroy superconductivity; $H_0$ (also called $H_c(0)$) = critical field at 0 K; $T<T_c$ superconducting, $T>T_c$ normal; field above critical value restores normal state.
$$H_c(T)=H_0\left[1-\left(\frac{T}{T_c}\right)^{2}\right]$$
  - $H_c(T)$ = critical field at temperature T (A/m); $H_0$ = critical field at 0 K (A/m); $T,T_c$ in kelvin. (Standard empirical form.)

**1.4 Meissner Effect**
- **Definition:** When a material is cooled below $T_c$ in a magnetic field, it **actively expels** the magnetic flux from its interior so that **B = 0** inside; superconductors are perfectly diamagnetic.
$$B=\mu_0(H+M)=0\ \Rightarrow\ M=-H,\qquad\chi=\frac{M}{H}=-1$$
  - $B$ = flux density (T); $H$ = applied field (A/m); $M$ = magnetisation (A/m); $\chi$ = susceptibility; $\mu_0=4\pi\times10^{-7}\text{ H/m}$.
- **Significance:** Distinct from the perfect diamagnetism that mere zero resistance would imply (via Lenz's law); a Meissner state is an equilibrium thermodynamic state independent of how it is reached. Basis of magnetic levitation.
- **Limitation:** Lost above $H_c$ (Type I) or above $H_{c2}$ (Type II) and above $T_c$.

**1.5 Type I vs Type II superconductors (draw table in exam)**
| Property | Type I | Type II |
|---|---|---|
| Critical temperature | Low (≈0–10 K) | High (> 10 K) |
| Critical field | Low (≈0.0000049 T to 1 T); single $H_c$ | High (> 1 T); two fields $H_{c1}$, $H_{c2}$ |
| Meissner effect | Perfect (complete) | Partial |
| Transition | Sharp, abrupt | Gradual; **mixed (vortex / intermediate) state** between $H_{c1}$ and $H_{c2}$ |
| Magnetism | Completely diamagnetic | Not completely diamagnetic |
| Also called | **Soft** superconductors | **Hard** superconductors |
| Material | Pure metals (Hg, Pb, Zn) | Alloys and ceramic oxides (NbTi, Nb₃Sn, YBCO) |
| Impurity effect | Slight impurity has little effect | Slight impurity greatly affects |
| Mixed state | Absent | Present |
| Magnets | Unsuitable for strong magnets | Suitable for strong electromagnets |
| BCS theory (per notes) | Explains | "Cannot explain" |
- **Type II behaviour:** below $H_{c1}$ full Meissner state; between $H_{c1}$ and $H_{c2}$ flux penetrates in vortices (normal cores, rest superconducting); above $H_{c2}$ normal.
- ⚠ **Examiner's flag:** the notes state BCS cannot explain Type II. In standard texts BCS explains conventional Type II too; only the high-$T_c$ ceramics are "unconventional". Write the notes' line in the table and add the caveat if you have room.
- **Advantages/disadvantages (notes):** Type I — works at low T, impurity insensitive, obeys Meissner, but low $H_c$, abrupt loss, less versatile. Type II — higher $T_c$, $H_c$ and current capacity, useful in high-speed computing, but impurity sensitive, partial Meissner, sensitive to temperature and field.

**1.6 Applications of Superconductivity**
- **MRI/NMR body scanners:** strong superconducting magnet makes hydrogen nuclei in body water/fat absorb then re-emit energy at a detectable frequency which a computer images.
- **Accelerator magnets:** large currents without loss give very strong fields (liquid-helium cooled).
- **Maglev trains:** superconducting magnets on the train interact with coils on the guideway; train levitates ≈ 4 inches and is propelled at high speed with low friction and noise.
- **Power transmission:** superconducting cables reduce loss by ≈90%.
- **Magnetometers and sensors** (medicine, seismography); **quantum computing** (superconducting qubits); high-speed computing.

#### 2. Formula & Constant Reference Sheet
| Item | Value / relation |
|---|---|
| Hg $T_c$ | 4.2 K |
| Liquid helium b.p. | ≈4 K (4.2 K) |
| Liquid nitrogen b.p. | 77 K |
| MgB₂ $T_c$ | 39 K |
| Cuprate (1986) | 35 K; Tl–Ca–Ba–Cu–O 125 K (1988) |
| Meissner | $B=0$; $\chi=-1$ |
| $H_c(T)$ | $H_0[1-(T/T_c)^2]$ |
| Persistent current lifetime | ≥ 100,000 yr (experimental) |

#### 3. Top 5 Most Repeated Exam Questions & Derivation Outlines
**Q1. Define superconductivity, critical temperature; differentiate a normal conductor from a superconductor (R–T graph).** — Define; Onnes 1911; plot ρ vs T showing abrupt drop at $T_c$; residual resistance in normal metal; HTS above 77 K.

**Q2. Explain the Meissner effect.** — $T>T_c$ flux penetrates; $T<T_c$ flux expelled, $B=0$; show $M=-H$, $\chi=-1$; distinguish from perfect conductor; levitation.

**Q3. Effect of magnetic field on superconductors; critical field vs temperature.** — Define $H_c$, $H_0$; curve $H_c(T)$ parabola; superconducting inside curve, normal outside.

**Q4. Distinguish Type I and Type II superconductors with magnetisation curves.** — Reproduce the table; sketch $-M$ vs $H$: sharp drop at $H_c$ (Type I) vs two critical fields with mixed state (Type II); examples.

**Q5. Applications of superconductors: MRI, maglev, accelerators, power transmission.** — Principle (zero resistance + strong field) for each with one-line working.

---

### Unit 2 - Chapter 2.3: Advanced Materials — Solid-State Batteries, Low-Loss Electronics, Graphene Superconductivity

#### 1. Complete Glossary of Definitions & Laws

**1.1 Solid-State Battery**
- **Definition:** Rechargeable battery using a **solid electrolyte** instead of a liquid/gel electrolyte.
- **Components:** positive electrode (cathode: LiCoO₂, LiNiMnCoO₂, LiFePO₄) supplies Li⁺ on discharge; negative electrode (anode: lithium metal) stores/releases Li⁺; **solid electrolyte** replaces liquid electrolyte **and** separator — conducts ions and mechanically separates electrodes.
- **Superionic electrolytes:** solids with very high ionic conductivity, comparable to or exceeding liquid electrolytes — rapid ion transport.
- **Advantages vs Li-ion:** higher energy density, improved safety (reduced fire risk), faster charging, compact design, long cycle life.
- **Applications:** electric vehicles (longer range), portable electronics, micro-electronics/sensors, grid-scale storage.

**1.2 Energy Loss in Electronic Devices**
- **Conduction (resistive) loss:** $P=I^{2}R$ heat in wires/resistors.
- **Switching loss:** energy dissipated during on/off transitions of transistors.
- **Leakage loss:** small currents when device is "off".
- **Core loss:** eddy currents and hysteresis in transformers and inductors.
- **Thermal effects:** heating degrades performance and lifetime.

**1.3 Strategies to minimise loss**
- **Circuit/architecture:** sub-threshold circuit design; **adiabatic logic** (energy recovery); power gating; clock gating; **DVFS** (dynamic voltage and frequency scaling); low-power components; power-management ICs; switching (not linear) power supplies.
- **Materials:** graphene and CNTs (high conductivity, low heat loss); **wide-bandgap semiconductors GaN and SiC** (high temperature/voltage, low loss); **superconductors / HTS** (zero resistance, no $I^2R$ loss); soft magnetic composites (low core loss); high-temperature low-sag (HTLS) conductors; high-k dielectrics and 2D materials (e.g., MoS₂) for low-power transistors.
- **Harvesting:** piezoelectric and thermoelectric devices, ambient energy (vibration, heat, solar).
- **Fabrication:** inkjet/screen printing, laser scribing, chemical vapour deposition (CVD), plasma-enhanced CVD (PECVD).

**1.4 Graphene and Graphene Superconductivity**
- **Graphene:** two-dimensional crystalline allotrope of carbon, atoms in a **hexagonal lattice**.
- **Graphene superconductivity:** when graphene layers are **twisted and stacked at a specific ("magic") angle**, the material becomes a two-dimensional superconductor that can be tuned between insulator and superconductor.
- **Biosensor:** analytical device that detects biological molecules (glucose, DNA, proteins) and converts the response into a measurable signal. **Graphene advantages:** high conductivity, large surface area, flexibility, biocompatibility, label-free real-time detection (cancer, COVID-19, HIV biomarkers), continuous glucose/sweat/pulse monitoring, point-of-care use.
- **Foldable smartphones:** graphene as transparent flexible conductor **replacing indium tin oxide (ITO)**; high electron mobility → faster response; quantum biosensors and wearable patches.

#### 2. Formula & Constant Reference Sheet
| Item | Relation |
|---|---|
| Resistive loss | $P=I^2R$ |
| HTS benefit | $R\to0\Rightarrow P_{loss}\to0$ |
| Li-ion half reaction (charging) | $\text{Li}^+$ intercalates into graphite anode |
| Typical Li cathodes | LiCoO₂, LiNiMnCoO₂, LiFePO₄ |

#### 3. Top 5 Most Repeated Exam Questions & Derivation Outlines
**Q1. Compare Li-ion and solid-state batteries; advantages and applications.** — Construction (liquid vs solid electrolyte+separator); table of safety, energy density, charging, lifespan; EV, grid.

**Q2. Explain the sources of energy loss in electronic devices and the methods to reduce them.** — Five loss types; circuit techniques (DVFS, clock gating, adiabatic); materials (GaN, SiC, HTS, graphene).

**Q3. What is graphene? How can graphene become superconducting?** — Hexagonal 2-D carbon; twisted bilayer at magic angle; tunable insulator/superconductor.

**Q4. Graphene-based biosensors: working and advantages.** — Biological recognition → electrical signal; list four graphene properties; applications.

**Q5. Role of high-temperature superconductors in low-loss power systems and electronics.** — Zero resistance ⇒ no $I^2R$; liquid nitrogen cooling; PV cells, grids, MRI, quantum computing.

---

# UNIT 3 — LASERS AND OPTICAL FIBRES

---

### Unit 3 - Chapter 3.1: Lasers

#### 1. Complete Glossary of Definitions & Laws

**1.1 LASER**
- **Definition:** **L**ight **A**mplification by **S**timulated **E**mission of **R**adiation — a very intense, concentrated, highly parallel, monochromatic and coherent beam of light.
- **Characteristics (five, as in notes):**
  1. **Directionality:** departs from parallelism only by diffraction; far less divergence than any lens/mirror-collimated lamp.
  2. **Coherence:** coherence length up to kilometres (tungsten lamp or discharge tube: < 1 m).
  3. **Monochromaticity:** discharge-line sharpness ≈ 1 part in $10^6$; laser ≈ 1 part in $10^9$ (≈1000× sharper).
  4. **Sharp focusing:** flux densities ≈ $10^{15}\text{ W cm}^{-2}$ achievable.
  5. **Brightness:** highest of any source; power emitted per unit area per unit solid angle.
- **Incoherent light:** ordinary sources (Sun, tungsten filament, tube light) — wide range of frequencies, directions, durations, random phase; from **spontaneous** emission.
- **Coherent light:** uniform frequency, amplitude and continuity with constant phase difference; from **stimulated** emission by atoms dropping from a metastable state.

**1.2 Three Atomic Interactions with Radiation**
| Process | Definition | Equation |
|---|---|---|
| **Induced (stimulated) absorption** | Atom in ground state $E_1$ absorbs a photon of $h\nu=E_2-E_1$ and goes to excited state $E_2$ | $A+h\nu\rightarrow A^{*}$ |
| **Spontaneous emission** | Excited atom returns to lower level without any external agent, emitting a photon (lifetime ≈ $10^{-8}$ s) | $A^{*}\rightarrow A+h\nu$ |
| **Stimulated emission** | An incident photon of energy $h\nu=E_2-E_1$ induces an excited atom to emit a second identical photon | $A^{*}+h\nu\rightarrow A+2h\nu$ |
- **Spontaneous emission features:** random direction, no phase relation (incoherent), less intense, different frequencies.
- **Stimulated emission features:** two photons identical in frequency, phase, direction and polarization; coherent, intense, monochromatic, unidirectional; **photon multiplication** occurs.

**1.3 Einstein Coefficients and Rate Equations**
- **$B_{12}$** = Einstein coefficient of stimulated absorption; **$A_{21}$** = Einstein coefficient of spontaneous emission (its reciprocal = lifetime of excited state); **$B_{21}$** = coefficient of stimulated emission.
- $u(\nu)$ = energy density of radiation ($\text{J m}^{-3}\text{ Hz}^{-1}$); $N_1,N_2$ = populations ($\text{atoms/m}^3$) of levels 1 and 2.
- **Rates:**
$$R_{ab}=N_1B_{12}u(\nu),\qquad R_{sp}=N_2A_{21},\qquad R_{st}=N_2B_{21}u(\nu)$$
- **Derivation of the relations (examinable):**
  1. Thermal equilibrium: $R_{ab}=R_{sp}+R_{st}$ ⇒ $N_1B_{12}u=N_2A_{21}+N_2B_{21}u$.
  2. Solve: $u(\nu)=\dfrac{A_{21}/B_{12}}{\dfrac{N_1}{N_2}-\dfrac{B_{21}}{B_{12}}}$.
  3. Boltzmann: $\dfrac{N_1}{N_2}=e^{h\nu/kT}$ ⇒ $u(\nu)=\dfrac{A_{21}/B_{12}}{e^{h\nu/kT}-B_{21}/B_{12}}$.
  4. Compare with Planck: $u(\nu)=\dfrac{8\pi h\nu^{3}}{c^{3}}\dfrac{1}{e^{h\nu/kT}-1}$.
  5. Hence
$$\boxed{B_{12}=B_{21}},\qquad\boxed{\frac{A_{21}}{B_{21}}=\frac{8\pi h\nu^{3}}{c^{3}}}$$
- **Significance:** probability of absorption equals probability of stimulated emission; $A_{21}/B_{21}\propto\nu^{3}$ — spontaneous emission increasingly dominates at high frequency, so it is **harder to obtain laser action at higher frequencies** (UV/X-ray).

**1.4 Conditions for Amplification (Laser Action)**
1. **$N_2\gg N_1$** (population inversion — ground state normally more populated, so a non-equilibrium state is required).
2. **$A_{21}$ small** — upper level must be long-lived (**metastable**, ≈ $10^{-3}$ s vs $10^{-8}$ s for ordinary excited states).
3. **$u(\nu)$ high** — high photon density, maintained by the **optical resonator**.
- Stimulated emission dominates only if $u$ is high and $A_{21}$ is small; the laser operates when **optical gain exceeds optical losses**.

**1.5 Population Inversion**
- **Definition:** The state in which the number of atoms in the excited (higher) state exceeds that in the ground (lower) state, $N_2>N_1$.
- **Boltzmann distribution:** $N=N_0e^{-E/kT}$; so $N_1=N_0e^{-E_1/kT}$, $N_2=N_0e^{-E_2/kT}$, and at equilibrium $N_1>N_2$.
- **Why a two-level system cannot invert:** pumping only equalises populations; need a metastable level.
- **Three-level system:** levels $E_1<E_2<E_3$. Pump $E_1\to E_3$; $E_3$ has lifetime $10^{-8}$ s, atoms decay non-radiatively to **metastable $E_2$** (lifetime $10^{-3}$ s); atoms accumulate; inversion between $E_2$ and $E_1$.

**1.6 Pumping**
- **Definition:** Process of raising atoms to higher energy states (using photons/energy of frequency different from the stimulating frequency) to achieve population inversion.
- **Methods:**
  - **Optical pumping** — xenon flash tube; solid lasers with broad absorption bands (ruby, Nd:YAG, Nd:glass).
  - **Electrical discharge pumping** — gas lasers (narrow absorption bands; He-Ne, CO₂, argon-ion).
  - **Chemical pumping** — chemical reaction (HF, DF lasers).
  - **Injection-current pumping / direct conversion** — forward-biased semiconductor junction (GaAs, InP).

**1.7 Main Components of a Laser**
1. **Active (lasing) medium:** material in which inversion is possible (solid, liquid, gas); few "active centres" do the lasing, the rest is "host"; many lasers are named after it.
2. **Pump:** external energy source (optical, electrical, chemical, thermal).
3. **Optical resonator:** two mirrors with common axis, one nearly 100% reflecting (≈99%) and the other partially reflecting; acts as a **feedback device**, multiplies photons by repeated passes, gives **direction selectivity**, builds high photon density (standing-wave resonance).
- **Classification of lasers:** by medium — solid (ruby, Nd:YAG, Nd:glass), liquid (europium chelate, SeOCl₂), gas (CO₂, He-Ne, argon-ion), dye (rhodamine 6G), semiconductor (GaAs, InP); by pumping (flash, chemical, discharge); by output (pulsed or continuous wave, CW); by spectral region (UV, visible, IR).
- **Three-level laser:** inversion between the metastable level and the **ground state**; needs high pumping power; **ruby** is the example. **Four-level laser:** lasing between the 3rd and 2nd excited states, lower laser level rapidly depopulated; easier inversion; **He-Ne** is the example.

**1.8 Ruby Laser**
- **Type:** doped-insulator solid-state, three-level, pulsed. **Inventor:** Maiman, **1960** (first laser).
- **Active medium:** ruby = Al₂O₃ crystal in which ≈ **0.05%** (by weight) Al³⁺ replaced by **Cr³⁺** (active centres; gives pink/red colour by absorbing green and blue light).
- **Construction:** rod ≈ **4 cm long, 5 mm diameter**; ends polished, strictly parallel, silvered — one fully reflecting, the other partially; rod surrounded by helical **xenon flash tube** (pump); cooling arrangement (most of the flash energy appears as heat).
- **Working:** green/blue light from the flash raises Cr³⁺ ions from ground state to excited bands; they relax **non-radiatively** (energy goes to the lattice) to the metastable level (lifetime ≈ $10^{-3}$ s; notes also quote $\sim10^{-6}$ s in the narrative); population inversion between metastable level and ground; spontaneous photon along axis stimulates others; photons reflect between the silvered ends and multiply; intense coherent beam leaves via the partially silvered end.
- **Output:** pulsed red light, **λ = 6943 Å = 694.3 nm**.
- **Uses:** holographic portraits and non-destructive testing (aircraft), tattoo/hair/melanin removal, plasma diagnostics (electron density, temperature).
- **Drawbacks:** high pumping power (lasing level is the ground state — more than half the ground-state atoms must be pumped); very low efficiency (only the green component of pump light used); pulsed (µs duration), not continuous; crystal imperfections.

**1.9 Semiconductor (Diode) Laser**
- **Principle:** Specially fabricated **p-n junction diode** (direct band-gap, e.g., GaAs) that lases when **forward-biased**: electrons from n-side and holes from p-side recombine in the junction region and release **recombination radiation**; at high injection a population inversion forms between conduction and valence bands and stimulated emission occurs.
- **Wavelength:** $\lambda=\dfrac{hc}{E_g}$ ($E_g$ = band gap in J); GaAs gives infrared **8300–8500 Å**.
- **Construction:** single-crystal GaAs platelet with n- and p-regions; thin active layer (a few µm); end faces polished and parallel (act as resonator); electrodes for current.
- **Characteristics (notes):** solid-state; active medium GaAs p-n junction; **direct conversion** pumping; power ≈ 1 mW; CW or pulsed; threshold current density very large (≈ 400 A/mm²).
- **Advantages:** very small and compact, high efficiency, output controlled by junction current, works at low power, little auxiliary equipment, CW or pulsed.
- **Disadvantages:** hard to control mode pattern; large divergence (5°–15°); poorer purity/monochromaticity; high threshold current density; poor coherence and stability.
- **Uses:** fibre-optic communication, laser printers, CD/DVD read–write, healing wounds/pain relief (IR).

**1.10 Holography**
- **Definition:** Producing a three-dimensional image of an object by recording the interference pattern of light waves on a photographic plate; invented by **Dennis Gabor** (father of holography); Greek *holos* (whole) + *graphein* (write).
- **Hologram:** photograph of an interference pattern which, suitably illuminated by laser light, reconstructs a 3-D image; viewing from different angles gives different perspectives; **divisible** — each fragment contains the whole image.
- **Recording (step 1):** coherent laser beam split into a **reference beam** (undisturbed, goes straight to plate) and an **object beam** (strikes the object, reflects onto plate); the two **interfere** on a high-resolution film. Needs mirrors/prisms and beam divider.
- **Reconstruction (step 2):** illuminate the developed hologram with coherent light of the same frequency; the hologram acts as a **diffraction grating**; a **real image** forms where rays actually meet and a **virtual 3-D image** forms behind the plate; visible to the naked eye.
- **Photography vs holography:** photograph records only intensity (2-D), needs a lens, ordinary light, each part gives only part of the picture; hologram records amplitude **and phase** (3-D), needs no lens, uses laser light and interference, each part holds the full image.
- **Applications:** 3-D photography, biomedical, compact discs, grocery scanners, holographic interferometry, security holograms, data storage.

#### 2. Formula & Constant Reference Sheet
| Quantity | Relation / Value |
|---|---|
| Absorption rate | $R_{ab}=N_1B_{12}u(\nu)$ |
| Spontaneous emission rate | $R_{sp}=N_2A_{21}$ |
| Stimulated emission rate | $R_{st}=N_2B_{21}u(\nu)$ |
| Einstein relations | $B_{12}=B_{21}$; $A_{21}/B_{21}=8\pi h\nu^3/c^3$ |
| Ratio of rates | $R_{st}/R_{ab}=N_2/N_1$; $R_{st}/R_{sp}=\dfrac{1}{e^{h\nu/kT}-1}$ |
| Boltzmann | $N_2/N_1=e^{-h\nu/kT}$; $N=N_0e^{-E/kT}$ |
| Excited-state lifetime | $\tau=1/A_{21}\approx10^{-8}\text{ s}$; metastable ≈ $10^{-3}\text{ s}$ |
| Ruby λ | 6943 Å (694.3 nm), Cr³⁺ 0.05% |
| GaAs λ | 8300–8500 Å; $\lambda=hc/E_g$ |
| Laser light | monochromaticity $10^{-9}$; flux $10^{15}\text{ W/cm}^2$; coherence length km |

#### 3. Top 5 Most Repeated Exam Questions & Derivation Outlines
**Q1. Distinguish spontaneous and stimulated emission; explain absorption; characteristics of laser light.** — Three equations; list four features of each emission; five laser properties with numbers.

**Q2. Derive the relation between Einstein's coefficients $A_{21}$, $B_{12}$, $B_{21}$.** — Five-step derivation in §1.3; conclude $B_{12}=B_{21}$ and $A_{21}/B_{21}=8\pi h\nu^3/c^3$; interpret significance.

**Q3. What is population inversion? Explain conditions for amplification and pumping methods; explain the three-level scheme.** — Define; Boltzmann; three conditions; metastable role ($10^{-3}$ s); four pumping methods with examples.

**Q4. Explain construction and working of the ruby laser (with energy-level diagram); drawbacks; and/or the semiconductor laser.** — Fill the §1.8 template: type/medium/pump/resonator/output/λ; construction; working; drawbacks. For the diode laser use §1.9 with $\lambda=hc/E_g$.

**Q5. Explain holography: recording, reconstruction; difference from photography; applications of lasers.** — Reference + object beam; interference on film; reconstruction by diffraction; real and virtual image; table of contrasts.

---

### Unit 3 - Chapter 3.2: Fibre Optics

#### 1. Complete Glossary of Definitions & Laws

**1.1 Optical Fibre**
- **Definition:** A flexible, transparent fibre made by drawing glass (silica) or plastic to a diameter slightly thicker than a human hair; guides light between its two ends by **total internal reflection (TIR)**.
- **Structure:** **Core** (carries light; high refractive index; pure SiO₂ with dopants; telecom sizes 9, 50, 62.5 µm) → **Cladding** (lower refractive index; confines light; ≈125 µm) → **Coating/Jacket** (protective polymer such as polyurethane/PVC; absorbs shocks, nicks, moisture; no optical role).
- **Dopants:** **GeO₂, P₂O₅ raise** refractive index; **B₂O₃ and fluorine lower** it. Pure silica n ≈ 1.458 at 850 nm.
- **Types by material:** glass–glass (all-silica; e.g., GeO₂–SiO₂ core with SiO₂ cladding); plastic-clad glass (core ≈ 150–600 µm, cladding Teflon-PEP n = 1.338, short distance, high loss, LED source); plastic fibre POF (core 110–1400 µm; polystyrene core 1.6/cladding 1.49, NA 0.6; PMMA core 1.49/clad 1.40, NA 0.5; ≤ 100 m, high attenuation, cheap, easy to handle).
- **Uses:** communication (thousands of conversations simultaneously), medical endoscopes, light/image transmission to inaccessible places.

**1.2 Refractive Index and Snell's Law**
- **Refractive index:** $n=\dfrac{c}{v}$ — ratio of speed of light in vacuum to that in the medium (air ≈ 1; water 1.33; silica glass ≈ 1.45–1.48).
- **Snell's law:** $n_1\sin\theta_1=n_2\sin\theta_2$; $n_1,n_2$ refractive indices of the first and second media; $\theta_1,\theta_2$ angles of incidence and refraction measured from the normal. A ray entering normally ($\theta_1=0$) is not bent. Going into a denser medium the ray bends towards the normal; into a rarer medium, away from it.

**1.3 Critical Angle and Total Internal Reflection**
- **Critical angle $\theta_c$:** the angle of incidence in the denser medium ($n_1>n_2$) for which the angle of refraction is 90° (refracted ray grazes the interface).
$$\sin\theta_c=\frac{n_2}{n_1}\quad(n_1>n_2)$$
- **Total internal reflection:** For $\theta>\theta_c$ and $n_1>n_2$, light is entirely reflected back into the denser medium. **Conditions:** light travels from denser to rarer medium **and** incidence angle exceeds critical angle.
- **Principle of optical fibre:** repeated TIR at the core–cladding boundary.

**1.4 Acceptance Angle and Acceptance Cone**
- **Acceptance angle $\theta_0$ ($\theta_{max}$):** maximum angle (with the fibre axis) at which a ray can enter the core face and still be guided by TIR.
- **Acceptance cone:** cone obtained by rotating $\theta_0$ about the axis (full angle $2\theta_0$); rays outside refract into the cladding and are lost.
- **Derivation (outline):** Ray from medium $n_0$ (air = 1) enters the core at $\theta_0$, refracts at $\theta_r$: $n_0\sin\theta_0=n_1\sin\theta_r$. At the core–cladding interface the angle of incidence is $(90^\circ-\theta_r)$; for the limiting TIR case $\sin(90^\circ-\theta_r)=\cos\theta_r=n_2/n_1$. So $\sin\theta_r=\sqrt{1-n_2^2/n_1^2}$ and
$$n_0\sin\theta_0=\sqrt{n_1^{2}-n_2^{2}}\ \Rightarrow\ \theta_0=\sin^{-1}\!\left(\frac{\sqrt{n_1^{2}-n_2^{2}}}{n_0}\right)$$
- Depends only on $n_1$, $n_2$ (and $n_0$); larger $\theta_0$ → more light accepted.

**1.5 Numerical Aperture (NA)**
- **Definition:** A measure of the ability of a fibre to collect (gather) and confine light; the light-gathering efficiency.
$$NA=n_0\sin\theta_0=\sqrt{n_1^{2}-n_2^{2}}\approx n_1\sqrt{2\Delta},\qquad \Delta=\frac{n_1-n_2}{n_1}$$
  - $\Delta$ = relative (fractional) refractive-index difference (dimensionless); NA is dimensionless.
- **Properties:** depends only on refractive indices, **not** on fibre dimensions; typical range **0.13–0.5**; large NA accepts more light (but gives more modal dispersion).

**1.6 V-number (Normalized Frequency) and Number of Modes**
- **Definition:** Parameter determining how many modes the fibre supports.
$$V=\frac{2\pi a}{\lambda}\,NA=\frac{2\pi a}{\lambda}\sqrt{n_1^{2}-n_2^{2}}$$
  - $a$ = core radius (m); $\lambda$ = operating wavelength (m).
- **Single-mode if $V<2.405$; multimode if $V>2.405$.** Number of modes (standard): $N\approx V^{2}/2$ (step index), $V^{2}/4$ (graded index).
- V can be reduced by decreasing NA or core diameter.

**1.7 Modes of Propagation**
- **Mode:** an allowed ray path/field pattern in which the waves undergoing repeated reflections are in phase (constructive interference); others die by destructive interference.
- **Lower-order modes:** travel near the axis, small angles, field concentrated at the centre, shorter path, arrive earlier. **Higher-order modes:** angles near critical, fields spread to the edge and into cladding, longer path, arrive later (delayed). **Zero-order mode:** axial ray.

**1.8 Types of Fibres (classification and comparison)**
| Feature | Single-mode step-index | Multimode step-index | Graded-index (GRIN) |
|---|---|---|---|
| Core diameter | 8–12 µm (notes example: radius 3 µm, NA 0.1 at 0.8 µm) | 50–100 µm | ≈ same as step-index MMF (50–100 µm) |
| Cladding diameter | ≈125 µm | 150–250 µm | ≈ similar |
| Index profile | uniform core, abrupt step | uniform core, abrupt step | core index decreases **parabolically** from the axis outward |
| Modes | only zero-order | many | many |
| Ray path | straight along axis | zig-zag (meridional rays) | **curved/sinusoidal** (continuous refraction + TIR) |
| Dispersion | negligible (no modal) | **highest modal dispersion** | very low modal dispersion |
| Bandwidth | highest (≈1000 MHz quoted) | lowest (can be ≈10 MHz·km) | intermediate |
| Source | laser diode needed | LED/laser | LED/laser |
| Cost / coupling | costly, hard to couple | cheap, easy to couple | moderate |
| Use | long haul | short distance LAN, data, audio/video | medium-distance links |
- **Why GRIN has equal arrival times:** rays at larger angles take longer paths but travel through lower-index regions (faster), so all modes have nearly the same optical path length and reach the end simultaneously.
- **Single-mode:** small Δ and NA by reducing core radius and Δ; low acceptance angle.

**1.9 Dispersion**
- **Definition:** Broadening of optical pulses as they travel along a fibre, caused by different propagation velocities of different frequencies/modes; leads to overlap of pulses and limits information capacity (bandwidth).
- **Intermodal (modal) dispersion:** different modes travel at different group velocities in a multimode fibre; greatest in multimode step-index; more modes ⇒ more dispersion. Standard estimate: $\Delta t\approx\dfrac{Ln_1}{c}\dfrac{(n_1-n_2)}{n_2}\approx\dfrac{Ln_1\Delta}{c}$.
- **Intramodal (chromatic) dispersion:** in single-mode fibre because light of different wavelengths travels at different speeds. Two parts: **material dispersion** (refractive index of glass varies with wavelength) and **waveguide dispersion** (dispersive phase shifts due to the guiding structure).

**1.10 Attenuation (Losses)**
- **Definition:** Reduction of optical power along the fibre, defined from the ratio of input power $P_{in}$ to output power $P_{out}$:
$$\alpha=\frac{10}{L}\log_{10}\frac{P_{in}}{P_{out}}\ \ \text{dB/km}$$
  - $L$ = fibre length (km); $P_{in},P_{out}$ in the same unit.
- **Types:**
  - **Absorption loss:** intrinsic (interaction with glass components; UV electronic bands) and extrinsic (impurities — Fe, Ni, Cr and water/OH ions); photon energy converted to heat.
  - **Scattering loss (linear):** intrinsic photon–glass interaction; deflection by irregularities.
  - **Bending loss:** **microbend** (small discontinuities, uneven coating, external forces) and **macrobend** (large-radius bends; significant when radius < a few cm).

**1.11 Advantages and Disadvantages of Optical-Fibre Communication**
- **Advantages:** cheap raw material (silica); small, light (RG-19/U coax ≈ 1100 kg/km vs fibre cable ≈ 6 kg/km), flexible; non-hazardous (insulating, no sparks); **immune to EMI/RFI** (photons are neutral); **no cross-talk** (light trapped, secure); wide bandwidth (900-pair telephone cable ≈ 10,000 calls vs 1 mm fibre ≈ 50,000 calls); low loss (≈ 4 dB/km as quoted) — repeaters every ≈100 km vs ≈2 km for copper.
- **Disadvantages:** specialist installation skills, installation cost, cost of electrical–optical conversion equipment, cannot carry electrical power.

#### 2. Formula & Constant Reference Sheet
| Quantity | Formula |
|---|---|
| Refractive index | $n=c/v$ |
| Snell's law | $n_1\sin\theta_1=n_2\sin\theta_2$ |
| Critical angle | $\sin\theta_c=n_2/n_1$ |
| Acceptance angle | $\sin\theta_0=\sqrt{n_1^2-n_2^2}/n_0$ |
| Numerical aperture | $NA=\sqrt{n_1^2-n_2^2}=n_1\sqrt{2\Delta}$ |
| Fractional index difference | $\Delta=(n_1-n_2)/n_1$ |
| V-number | $V=(2\pi a/\lambda)NA$ |
| Single-mode condition | $V<2.405$ |
| Number of modes | $N\approx V^2/2$ (SI), $V^2/4$ (GRIN) |
| Modal dispersion | $\Delta t\approx Ln_1\Delta/c$ |
| Attenuation | $\alpha=(10/L)\log_{10}(P_{in}/P_{out})\text{ dB/km}$ |
| Typical NA | 0.13–0.5 |
| Typical core / cladding | SMF 8–12 / 125 µm; MMF 50–100 / 150–250 µm |

#### 3. Top 5 Most Repeated Exam Questions & Derivation Outlines
**Q1. Explain the construction and principle of an optical fibre; define critical angle and TIR; give conditions for TIR.** — Core/cladding/coating with $n_1>n_2$; Snell's law at $\theta_2=90^\circ$ ⇒ $\sin\theta_c=n_2/n_1$; two conditions.

**Q2. Derive the expression for acceptance angle and numerical aperture.** — Steps in §1.4: Snell at the face, TIR condition at the interface, eliminate $\theta_r$; give $NA=\sqrt{n_1^2-n_2^2}\approx n_1\sqrt{2\Delta}$; acceptance cone.

**Q3. Classify optical fibres and compare single-mode, multimode and graded-index fibres (with index profiles and ray paths).** — Reproduce the §1.8 table; draw the three index profiles and ray paths; explain equal transit times in GRIN.

**Q4. What is dispersion? Explain intermodal and intramodal dispersion.** — Define pulse broadening; modal (greatest in MM step-index) with $\Delta t$ formula; chromatic = material + waveguide; remedy GRIN/SMF.

**Q5. Explain attenuation and its causes; numerical on NA / V-number / dB-loss; advantages of fibre communication.** — Absorption (intrinsic/extrinsic), scattering, micro/macro bending; $\alpha$ formula; V-number rule 2.405; list seven advantages.

---

### Unit 3 - Chapter 3.3: Applications of Lasers and Optical Fibres

#### 1. Complete Glossary of Definitions & Laws

**1.1 Applications of Lasers (property → use)**
- **Property basis:** coherence, monochromaticity, directionality, high intensity.
- **Medical:** laser scalpel (CO₂ for soft tissue, Nd:YAG for deep tissue); bloodless surgery; **LASIK** (corneal reshaping for myopia, hyperopia, astigmatism); photocoagulation and welding of detached retina (diabetic retinopathy); capsulotomy; tumour/infected-cell removal; dental drilling; dermatology (tattoo and hair removal, skin resurfacing, vascular lesions).
- **Industrial:** cutting and welding (CO₂, fibre lasers; focus gives ≈1000 K local heating in the notes); drilling, melting and fusing; engraving/marking; **3-D printing** (SLS, DMLS).
- **Communication:** modulated laser beams, laser diodes in fibre links, free-space optical links (buildings/satellites), deep-space laser communication (NASA tests).
- **Measurement:** ranging of long distances — Apollo 11 (20 July 1969) retro-reflector on the Moon; Earth–Moon distance to within 6 m, later 30 cm; LIDAR; laser altimetry (Mars orbiters).
- **Nuclear fusion:** laser focused on a tiny spot, temperature ≈ $10^8$ K.
- **Scientific research:** spectroscopy (Raman, LIBS), interferometry (Michelson–Morley experiment; LIGO), laser cooling and trapping of atoms (atomic clocks, quantum computing).
- **Military:** range-finding, target designation, directed-energy weapons (high-energy lasers), LIDAR in surveillance.
- **Consumer/entertainment:** CD/DVD/Blu-ray, barcode scanners, laser shows, holography/security holograms.

**1.2 Applications of Optical Fibres**
- **Telecommunications/Internet:** FTTH broadband, long-distance telephony, cellular backhaul, submarine intercontinental cables.
- **Medical:** endoscopy, fibre-guided laser surgery, biomedical sensors (pressure, temperature, chemical levels).
- **Military/Aerospace:** secure tap-proof communications, fibre-optic gyroscopes for guided-missile navigation, lightweight aircraft data systems.
- **Industrial/Sensing:** temperature/pressure sensing in oil and gas pipelines, **structural health monitoring** of bridges and tunnels, industrial automation immune to EMI, intrusion detection (vibration along fences).
- **Broadcasting/Entertainment:** HD video (4K/8K), cable TV, stage lighting.
- **Data centres/Networking:** server interconnects, cloud backbones, fibre-to-the-desk.
- **Transportation:** railway signalling, traffic monitoring and smart signals, in-vehicle networks.
- **Sensors based on fibres and lasers (syllabus):** fibre sensors detect changes in light intensity, phase or wavelength caused by pressure, temperature, strain or vibration; laser sensors use LIDAR/range-finding; benefits — real-time, remote, durable, high sensitivity.

#### 2. Formula & Constant Reference Sheet
| Item | Value |
|---|---|
| Moon ranging accuracy | 6 m (1969) → 30 cm |
| Fusion temperature with laser | ≈ $10^8$ K |
| Industrial focused heating (notes) | ≈ 1000 K |
| Typical medical lasers | CO₂ (soft tissue), Nd:YAG (deep), ruby (tattoo/hair removal) |

#### 3. Top 5 Most Repeated Exam Questions & Derivation Outlines
**Q1. List and explain applications of lasers in medicine, industry, communication and military.** — Match each application to a laser property (precision = directionality; cutting = high intensity; communication = coherence/low loss).

**Q2. Application of lasers in measurement of long distances (Moon) and nuclear fusion.** — Retro-reflector, round-trip time, $d=ct/2$; accuracy 6 m → 30 cm; fusion at $10^8$ K from tight focusing.

**Q3. Applications of optical fibres in communication and medicine (endoscope).** — FTTH, submarine cable, EMI immunity; endoscope light-guide and image bundle; fibre-guided laser surgery.

**Q4. Fibre-optic sensors and structural-health monitoring.** — Principle (physical change modifies guided light), examples (pipelines, bridges, fence intrusion), advantages.

**Q5. Compare optical-fibre and copper-cable communication.** — Bandwidth, loss (repeater spacing 100 km vs 2 km), weight (6 vs 1100 kg/km), EMI, cross-talk, safety; disadvantages.

---

# MASTER CONSTANT TABLE (all units)
| Constant | Symbol | Value |
|---|---|---|
| Planck constant | $h$ | $6.626\times10^{-34}\text{ J}\cdot\text{s}$ |
| Reduced Planck constant | $\hbar$ | $1.055\times10^{-34}\text{ J}\cdot\text{s}$ |
| Speed of light | $c$ | $3\times10^{8}\text{ m/s}$ |
| Boltzmann constant | $k$ | $1.38\times10^{-23}\text{ J/K}$ |
| Electron mass | $m_e$ | $9.1\times10^{-31}\text{ kg}$ |
| Proton / neutron mass | $m_p,m_n$ | $1.673\times10^{-27}$, $1.676\times10^{-27}\text{ kg}$ |
| Elementary charge | $e$ | $1.6\times10^{-19}\text{ C}$ |
| Avogadro number | $N_A$ | $6.022\times10^{23}\text{ mol}^{-1}$ |
| Electron-volt | eV | $1.6\times10^{-19}\text{ J}$ |
| Ångström / nanometre | Å / nm | $10^{-10}\text{ m} / 10^{-9}\text{ m}$ |
| Permeability of free space | $\mu_0$ | $4\pi\times10^{-7}\text{ H/m}$ |
| Electron wavelength (V volts) | $\lambda$ | $12.27/\sqrt V\text{ \AA}$ |
| $hc$ | | $12400\text{ eV}\cdot\text{\AA}$ |

*End of compendium.*
