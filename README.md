<h1 align="center">Hi there, I'm Rithik Rai! 👋</h1>

<h3 align="center">Quantum Computing Fellow | Physics Master's Graduate</h3>

<p align="center">
  Bridging the gap between fundamental physics and cutting-edge computational challenges, particularly in optimization and simulation.
</p>

<p align="center">
  <a href="https://in.linkedin.com/in/iarithik" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://flowcv.com/resume/prd61bomfe" target="_blank">
    <img src="https://img.shields.io/badge/Resume-432874?style=for-the-badge&logo=reverbnation&logoColor=white" alt="Resume" />
  </a>
</p>

---

### 🎓 Background & Community

*   🎓 **Education:** Master's in Physics from [CUSAT](https://www.cusat.ac.in/) | Bachelor's in Physics from [SIES College](https://siesascs.edu.in/).
*   👨‍🏫 **Community:** Quantum Computing Instructor at [QWorld](https://qworld.net/) | Mentor for [Womanium & Wiser Quantum Program](https://www.thewiser.org/quantum-programs).
*   🏆 **Achievements:** Top 5 performer in the[CDAC India - Qniverse Developer Certification Exam](https://qniverse.in/certificate/).

### 💻 Technical Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat-square&logo=qiskit&logoColor=white)
![PennyLane](https://img.shields.io/badge/PennyLane-000000?style=flat-square&logoColor=white)
![D-Wave](https://img.shields.io/badge/D--Wave_Ocean-0080FF?style=flat-square&logoColor=white)
![Classiq](https://img.shields.io/badge/Classiq-12100E?style=flat-square&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=flat-square&logo=pandas&logoColor=white)

**Core Concepts:** QUBO Modelling • Simulated & Quantum Annealing • Quantum Circuits • Noise Modelling • Error Mitigation

---

### 🔬 Research Experience

*   **[Quantum Approaches to Vehicle Routing Problems (VRP)](https://github.com/Mr-Jamatia/Quantum-Vehicle-Routing-Problems)**
    *   Formulated QUBO models and implemented Full Qubo Solver (FQS) and Average Partitioning Solver (APS) using the D-Wave Ocean SDK. 
    *   Developed a graph-coarsening pipeline to scale VRP instances, significantly improving solver runtime on large graphs.
*   **Master's Thesis: Gravitational Waves and Quasinormal Modes**
    *   Completed a comprehensive theoretical review as a Fellow at [IIT Guwahati](https://www.iitg.ac.in/), exploring the advanced mathematical frameworks of astrophysical phenomena.

### 🚀 Projects

*   **[VQE Molecular Ground State Simulation for H2](https://github.com/iarithik/VQE-Molecular-GroundState-Sim)**\
_*Independent Project*_
    *   **Implementation:** Implemented a physics-informed Variational Quantum Eigensolver (VQE) using PennyLane, JAX, and Optax to calculate the ground-state energy of an H₂ molecule.
    *   **Circuit Optimization:** Parameterized the ansatz by explicitly mapping to a minimal basis set (STO-3G) and restricting the search space to the singlet state ($m_s = 0$), avoiding black-box hardware-efficient ansatzes.
    *   **Custom Training Loop:** Bypassed standard QML optimizers to construct a custom JIT-compiled Stochastic Gradient Descent loop with a strict convergence tolerance ($\Delta E \leq 10^{-6}$).
*   **[Quantum Algorithm for Solving Linear Differential Equations (Harmonic Oscillator)](https://github.com/iarithik/Girls-In-Quantum-QHackathon)**\
_[QHackathon 2026 (Classiq Track)](https://www.girlsinquantum.com/) | Team project of 3 members_
    * **Implementation:** Translated a theoretical quantum algorithm ([Xin et al., 2020](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.101.032307)) into a working Classiq SDK model to solve the 2nd-order LDE of a Quantum Harmonic Oscillator using the Truncated Taylor Series (LCU) method. 
    * **Energy Computation:** Mapped the time evolution of the system to a quantum circuit, successfully extracting the physical Kinetic and Potential Energies directly from the work qubit's measurement probabilities.
    * **Circuit Optimisation:** Mathematically proved the redundancy of the routing ancilla qubit (a_1) for closed systems (b=0). By stripping this out of the synthesis model, reduced the circuit width by 25% and depth by ~50% compared to the original compiler.
*   **[Quantum Walk — Galton Board Implementation](https://github.com/iarithik/Quantum-Walk)**\
_*[Womanium & WISER Quantum Program 2025](https://www.thewiser.org/) | Team project of 3 members*_
    *   **Implementation:** Implemented the Galton Board using quantum circuits based on ([Carney & Varcoe, 2022](https://arxiv.org/abs/2202.01735)); demonstrated how quantum interference produces a qualitatively different probability distribution from the classical case, with destructive interference creating a valley at the centre rather than the Gaussian peak.
    *   **Research & Correction:** Identified and documented multiple discrepancies between the reference paper's stated derivations and the correct theoretical predictions for specific interference configurations; recorded corrections in a dedicated GitHub repository. See: [github.com/iarithik/Corrections-to-Universal-Statistical-Simulator-arXiv-2202.01735](https://github.com/iarithik/Corrections-to-Universal-Statistical-Simulator-arXiv-2202.01735)
*   **[Optimising Battery Temperature for Electric Vehicles Using Quantum Annealing](https://github.com/iarithik/Optimising-Battery-Temperature-for-Electric-Vehicles-Using-Quantum-Annealing)**\
_*[Womanium Global Quantum + AI Program 2024](https://www.womanium.org/) | Team project of 4 members*_
    *   **Implementation:** Optimised battery temperature in lithium-ion EV batteries using quantum annealing to maintain State of Charge (SoC) and improve State of Health (SoH); processed NASA battery datasets, formulated the optimisation as a QUBO model, and implemented solutions on D-Wave's quantum annealer to minimise temperature.
    
### 📚 Learning Resources

*   **[PennyLane Codebook Solutions:](https://github.com/iarithik/Notes-Pennylane)** My personal solutions and learning notes covering quantum machine learning and quantum circuits using PennyLane. 
*   **[Classiq Solutions:](https://github.com/iarithik/Notes-Classiq)** Explorations, tutorials, and classical/quantum algorithm solutions built while learning algorithm design via the Classiq platform.

---

<p align="center">
  <img src="https://hitscounter.dev/api/hit?url=https%3A%2F%2Fgithub.com%2Fiarithik&label=Visitors&icon=heart-fill&color=%23432874&message=&style=flat&tz=UTC" alt="Visitor Badge" />
</p>
