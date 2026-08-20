# Hi, I'm Guilherme Garcia 👋🚀

🎓 Aerospace Engineer — University of Brasília (UnB), 2024  
📍 Brasília, Brazil  
🔧 MATLAB • CAD • CFD  
🌎 Open to remote & international opportunities  

---

## 🛠️ Technical Skills

| Area | Tools |
|------|-------|
| CFD Simulation | ANSYS Fluent, OpenFOAM |
| CAD Modeling | SolidWorks, CATIA |
| Programming | MATLAB, Simulink |
| Currently Learning | Python, Git |

---

## 🚀 Projects

# 🚀 Aerospace Engineering — Project Portfolio

Collection of CFD simulations, FEA structural analyses, and experimental
propulsion research developed during the Aerospace Engineering program
at the University of Brasília (UnB).

> Projects combine analytical solutions, numerical simulations, and
> experimental validation — consistently achieving errors below 5%
> against theoretical references.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Guilherme_Garcia-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/guilherme-garcia-guedes-aeroespacial/)
![ANSYS](https://img.shields.io/badge/ANSYS-Fluent_&_Structural-yellow?style=flat)
![CATIA](https://img.shields.io/badge/CAD-CATIA-blue?style=flat)
![MATLAB](https://img.shields.io/badge/MATLAB-Scripts-orange?style=flat)
![UnB](https://img.shields.io/badge/University-UnB_2024-green?style=flat)

---

## ⭐ Featured Project

### 🔥 [Hybrid Rocket — Slab Burner Design, Testing & Liquid Film Analysis](https://github.com/GuilhermeGarciaAero/hybrid-rocket-slab-burner-paraffin-analysis)

> 📄 [Published Thesis — UnB Digital Library](https://bdm.unb.br/handle/10483/39892)

Design, fabrication, experimental testing, and CFD simulation of a slab
burner for hybrid rocket propulsion research. Investigated liquid film
regression mechanisms of paraffin/LDPE fuel grains with gaseous oxygen
(GOx) as the oxidizer, combining experimental results with a validated
regression rate model.

| Area | Details |
|------|---------|
| CAD | CATIA — full 3D burner design + manufacturing drawings |
| CFD | ANSYS Fluent — internal flow & oxidizer field analysis |
| Experimental | Slab burner testing with paraffin/LDPE grains at varying ratios |
| Output | Liquid film regression rate model validated experimentally |

**Regression rate model:**

$$\dot{r}_{lf} = 1.576 \times 10^{-5} \cdot G_{ox}^{0.56} \cdot \mu_l^{-0.28042}$$

> 🔬 PIBIC Research + Bachelor's Thesis (TCC) — UnB, 2024

---

## 📂 All Projects

### ✈️ [CFD Analysis — NACA 23018 Airfoil (Viscous Flow)](https://github.com/GuilhermeGarciaAero/cfd-naca23018-viscous-flow-ansys)

Full aerodynamic analysis of the NACA 23018 airfoil under viscous
incompressible flow using ANSYS Fluent 2022 R1 with k-ε turbulence
model. Results validated against Xfoil and thin airfoil theory.

| Parameter | Value |
|-----------|-------|
| Angles of attack | -1.2°, 0°, 6°, 9.75°, 16° |
| Mesh | 343,035 nodes / 342,000 elements |
| Turbulence model | k-ε (Launder & Spalding) |
| Validation | Xfoil + panel method |

---

### 🌊 [CFD — Flat Plate Boundary Layer](https://github.com/GuilhermeGarciaAero/cfd-flat-plate-boundary-layer)

Numerical simulation of laminar boundary layer development over a flat
plate using ANSYS Fluent 2021 R2. Results validated against the
classical Blasius analytical solution.

| Tool | Boundary Condition | Key Output |
|------|--------------------|------------|
| ANSYS Fluent | Velocity Inlet / Pressure Outlet | Velocity & BL thickness profiles |

---

### 🏗️ [Buckling Analysis — Steel Beam (C-Section)](https://github.com/GuilhermeGarciaAero/buckling-analysis-steel-beam-ansys)

Critical buckling load of a cantilevered steel C-section beam.
Euler's formula compared with Eigenvalue Buckling FEA.

| Material | B.C. | Analytical | Numerical | Error |
|----------|------|------------|-----------|-------|
| Steel (E=200 GPa) | Fixed-Free | 1359.3 N | 1331.8 N | 2.06% |

---

### 🏗️ [Buckling Analysis — Aluminum Beam (Rectangular)](https://github.com/GuilhermeGarciaAero/buckling-analysis-aluminum-beam-ansys)

Critical buckling load of a simply supported aluminum rectangular beam.
Euler's formula compared with Eigenvalue Buckling FEA.

| Material | B.C. | Analytical | Numerical | Error |
|----------|------|------------|-----------|-------|
| Aluminum Alloy 3 (E=70 GPa) | Pinned-Pinned | 20985.25 N | 21777 N | 3.77% |

---

### 🛢️ [Pressure Vessel — Stress & Strain Analysis](https://github.com/GuilhermeGarciaAero/pressure-vessel-stress-analysis-ansys)

Stress state and circumferential strain of a thin-walled steel pressure
vessel. Thin-wall theory validated against FEA (¼ symmetry model).

| Stress Component | Analytical | Numerical | Error |
|------------------|------------|-----------|-------|
| Hoop (σ₁) | 168 MPa | 171.63 MPa | 2.11% |
| Longitudinal (σ₂) | 84 MPa | 82.829 MPa | 1.39% |
| Radial (σ₃) | 6 MPa | 6.0701 MPa | 1.15% |
| Strain (ε) | 0.000714 | 0.0007429 | 3.89% |

---

## 🛠️ Tools & Skills

| Area | Tools |
|------|-------|
| CFD | ANSYS Fluent, k-ε turbulence model |
| FEA / Structural | ANSYS Static Structural, Eigenvalue Buckling |
| CAD / Geometry | CATIA, ANSYS DesignModeler |
| Programming | MATLAB |
| Experimental | Slab burner testing, fuel grain fabrication |
| Analytical Methods | Euler Buckling, Thin-Wall Theory, Blasius, Kutta-Joukowski |

---

## 📈 Results Summary

All numerical projects achieved errors below **5%** against analytical
or experimental references, validating mesh quality and simulation setup.

| Project | Type | Max Error |
|---------|------|-----------|
| 🔥 Hybrid Rocket Slab Burner | Experimental + CFD + CAD | — |
| ✈️ NACA 23018 Airfoil CFD | CFD Viscous | ~14.7% (Cl at α=6°)* |
| 🌊 Flat Plate Boundary Layer | CFD | Blasius validated |
| 🏗️ Buckling — Steel Beam | FEA | 2.06% |
| 🏗️ Buckling — Aluminum Beam | FEA | 3.77% |
| 🛢️ Pressure Vessel | FEA | 3.89% |

*Higher deviation at α=6° attributed to mesh refinement limits
of ANSYS Student license.

---

## 👨‍💻 Author

**Guilherme Garcia Guedes**
Aerospace Engineer — University of Brasília, UnB (2024)
📍 Brasília, Brazil | 🌎 Open to remote & international opportunities

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Guilherme_Garcia-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/guilherme-garcia-guedes-aeroespacial/)
[![Thesis](https://img.shields.io/badge/TCC-UnB_Digital_Library-green?style=flat)](https://bdm.unb.br/handle/10483/39892)
---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/guilherme-garcia-guedes-aeroespacial/)

📧 guigguedes@gmail.com
---

*Aerospace Engineer passionate about fluid dynamics, structural 
analysis and computational simulations.*
