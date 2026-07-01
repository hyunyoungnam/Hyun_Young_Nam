# Hyun-Young Nam
### Scientific Machine Learning | Computational Mechanics | AI-Driven Engineering

- **Location**: Daejeon, South Korea
- **Email**: hyunyoungnam@kisti.re.kr

---

## Summary

**Researcher** at Korea Institute of of Science and Technology Information (KISTI).

Experienced in automating finite element simulation workflows. Through developing tools for programmatic model generation, I identified a critical bottleneck in Scientific Machine Learning (SciML): the difficulty of scaling diverse, physically-valid datasets using commercial solvers. Broadly, I aim to advance AI-driven engineering by integrating machine learning with traditional design principles. More specifically, I am focused on developing agentic frameworks-utilizing knowledge graphs and automated review loops-to bridge the gap between high-fidelity FEA and autonomous discovery in Scientific Machine Learning (SciML), including PINNs and Neural Operators.

---

## Research Areas

**Scientific Machine Learning**: PINNs, Neural Operators (DeepONet, Transolver), Physics-Informed Training

**Computational Mechanics**: FEM, Method of Finite Spheres, Explicit Dynamics, Fracture Mechanics

**Autonomous Engineering**: Multi-Agent Systems, Agentic HPO, Knowledge Graphs, Automated FEM Pipelines

---

## Skills

- **Programming**: Python, C++, MATLAB
- **Commerical FEM software**: Abaqus, ANSYS Mechanical
- **ML / Scientific computing**: PyTorch, NumPy/SciPy
- **Interests**: Scientific Machine Learning (SciML) - Physics-Informed Learning (PINNs) and Neural Operators (DeepONet); Autonomous Engineering Design via Multi-Agent Systems.

---

## Experience

### Researcher — KISTI  |  2026.07 – Present

- Researcher in Large-scale AI Research Center

### Researcher — Stealth Startup  |  2025.02 – 2026.01

- Developing software that automatically generates **editable** simulation inputs for **AI model training**, including **Abaqus `.inp`** files and **ANSYS Mechanical `.dat`** files.
- Constructing **automated pipelines** to scale **diverse, physically-valid dataset generation** by parameterizing geometry, material properties, and boundary conditions for SciML learning

---

## Education

- **Ph.D.**, Brown University — Mechanics of Solids and Structures (Providence, Rhode Island)  |  2023.09 – 2024.05 (droup out)
- **M.S.**, Brown University — Mechanics of Solids (Providence, Rhode Island)  |  2021.09 – 2023.05  
- **B.S.**, Kyungpook National University — Mechanical Engineering (Daegu, South Korea)  |  2015.03 – 2021.08

---

## Projects

### PIANO: Physics-Informed Agentic Neural Operator

A self-improving surrogate framework for computational fracture mechanics. PIANO combines the **Transolver** neural operator with physics-informed losses and a **multi-agent HPO system** that autonomously diagnoses training issues, debates fixes, and proposes new configurations — without manual tuning.

**Key Features**:
- **Transolver Neural Operator**: Physics-Attention transformer for learning PDE solutions on unstructured meshes
- **Multi-Agent HPO System**: LLM-based agents (Critic, Architect, Physicist) that diagnose and fix training issues autonomously
- **Physics-Informed Losses**: Equilibrium residual, strain energy, traction-free BC, J-integral consistency
- **Singularity-Aware Enrichment**: Polar coordinate features (r, log(r), θ/2 terms) for crack tip stress singularities
- **Adaptive Learning**: Active learning with uncertainty-based acquisition for efficient data collection

**Framework**: PyTorch, Transolver
**GitHub**: [PIANO](https://github.com/hyunyoungnam/Physics-Informed-Agentic-Neural-Operator)  

---

## Publications

- Nam, H.-Y., "Explicit dynamics with the method of finite spheres using a modified direct inverse mass matrix," *Computers and Structures*, Vol. 295, 2024. [DOI](https://doi.org/10.1016/j.compstruc.2024.107296)

### Method of Finite Spheres (MFS) - Key Concepts

**FEM vs MFS Comparison**

<img src="images/mfs_vs_fem.jpg" alt="FEM vs MFS Comparison" width="600">

*Comparison between Standard Finite Element Method (FEM) and Method of Finite Spheres (MFS), showing overlapping elements in MFS. MFS features simplified preprocessing, C¹ continuity, and robustness to irregular node distribution (Lai and Bathe, Computers & Structures, 2016).*

**Mass Lumping: FEM vs MFS**

<img src="images/mfs_vs_fem_mass_lumping.jpg" alt="Mass Lumping Comparison" width="300">

*Mass lumping comparison between Standard FEM and Method of Finite Spheres (MFS). The diagram illustrates the diagonal mass matrix structure for both methods, showing how MFS uses multiple basis functions (Shepard function and Linear) per node, resulting in a larger but structured mass matrix (Nam et al., Computers & Structures, 2024).*

---

## Contact

**Email**: hyun_young_nam@brown.edu
**ORCID**: [0009-0001-7704-7240](https://orcid.org/0009-0001-7704-7240)
**LinkedIn**: [linkedin.com/in/hyun-young-nam](https://www.linkedin.com/in/hyun-young-nam/)
**Google Scholar**: [Google Scholar](https://scholar.google.com/citations?user=ap0HKkYAAAAJ&hl=en&oi=sra)
