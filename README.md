# What-is-Quantum-AI

> A deep theoretical exploration of Quantum Mechanics × Quantum
> Computing × Artificial Intelligence

![hero](figures/hero.png)

------------------------------------------------------------------------

## 🔹 Introduction

This repository is a **theory-first** deep dive into the intersection of
**Quantum Mechanics**, **Quantum Computing**, and **Artificial
Intelligence (AI)**.\
It serves as a structured reference for students, researchers, and
enthusiasts who want to understand how quantum principles could reshape
AI and computing.

------------------------------------------------------------------------

## 🔹 What is Quantum Mechanics?

**Quantum Mechanics (QM)** is the fundamental physics that describes
nature at the smallest scales (atoms, photons, electrons).\
Key principles include:

-   **Superposition** -- A quantum system can exist in multiple states
    at once until measured.\
-   **Entanglement** -- Two particles can share a state such that
    changing one instantly changes the other, no matter the distance.\
-   **Uncertainty Principle** -- Certain properties (like position and
    momentum) cannot both be known precisely at the same time.\
-   **Wavefunction** -- A mathematical description of all possible
    states of a system.

------------------------------------------------------------------------

## 🔹 What is Quantum Computing?

**Quantum Computing (QC)** is the use of quantum mechanics to process
information in ways classical computers cannot.

-   **Qubits** -- Quantum bits, which can represent 0, 1, or both
    (superposition).\
-   **Quantum Gates** -- Operations that change qubit states (analogous
    to classical logic gates).\
-   **Quantum Circuits** -- Sequences of gates used to perform
    algorithms.\
-   **Quantum Algorithms** -- Algorithms like **Shor's (factoring)** or
    **Grover's (search)** that outperform classical methods.

Types of qubits being researched:\
- **Superconducting qubits** (Google, IBM, Rigetti)\
- **Trapped ions** (IonQ, Honeywell)\
- **Topological qubits** (Microsoft, Majorana quasiparticles)\
- **Photonic qubits** (Xanadu)

------------------------------------------------------------------------

## 🔹 What is Quantum AI?

**Quantum AI** is the fusion of quantum computing with artificial
intelligence.

Goals include:\
- Faster optimization and training of AI models.\
- Quantum-enhanced neural networks and support vector machines.\
- Solving problems intractable for classical AI (chemistry, medicine,
cryptography).

Potential applications:\
- **Drug discovery** (simulate molecules at quantum scale).\
- **Finance** (quantum optimization for portfolio management).\
- **Cybersecurity** (post-quantum cryptography).\
- **Materials science** (new superconductors, energy solutions).\
- **General AI** (faster learning via quantum-enhanced kernels).

------------------------------------------------------------------------

## 🔹 Key Terms & Definitions

-   **Qubit** -- Quantum bit, the smallest unit of quantum information.\
-   **Superposition** -- A qubit can exist in multiple states
    simultaneously.\
-   **Entanglement** -- Correlation between qubits beyond classical
    physics.\
-   **Quantum Teleportation** -- Transfer of quantum state from one
    place to another using entanglement.\
-   **Decoherence** -- Loss of quantum information due to environment
    interaction.\
-   **Quantum Supremacy** -- The point where a quantum computer performs
    tasks infeasible for classical ones.\
-   **Majorana Fermions** -- Exotic particles (or quasiparticles)
    theorized to be their own antiparticles, promising for robust
    topological qubits.\
-   **Error Correction** -- Methods to stabilize fragile quantum
    information.

------------------------------------------------------------------------

## 🔹 How Quantum AI Could Change the World

1.  **Healthcare & Medicine**
    -   Personalized drugs, protein folding, cancer detection (AI +
        quantum simulation).\
2.  **Climate & Energy**
    -   Design of room-temperature superconductors, new batteries,
        efficient solar panels.\
3.  **Finance & Economics**
    -   Portfolio optimization, risk analysis, fraud detection.\
4.  **Security & Cryptography**
    -   Threats to RSA encryption → rise of post-quantum cryptography.\
5.  **Artificial Intelligence**
    -   Quantum kernels, variational quantum classifiers, and QNNs could
        speed up learning.

------------------------------------------------------------------------

## 🔹 Recent Breakthroughs

-   **Quantum Supremacy (2019)** -- Google's Sycamore processor solved a
    sampling problem in 200 seconds that would take classical computers
    \~10,000 years.\
-   **Majorana Quasiparticles (2020s)** -- Advances suggest stability
    for topological qubits, potentially solving error correction
    bottlenecks.\
-   **Quantum Teleportation** -- Achieved experimentally across fiber
    and free space.\
-   **Superposition Experiments** -- Larger molecules placed in
    superposition, proving quantum effects at mesoscopic scales.\
-   **Quantum AI Demos** -- Companies like IBM, Xanadu, and Google have
    demonstrated small-scale quantum-enhanced machine learning tasks.

------------------------------------------------------------------------

## 🔹 Repo Structure

``` bash
What-is-Quantum-AI/
├── README.md
├── docs/              # Detailed explanations
├── theory/            # Your theoretical notes
├── src/               # Simulation code (optional)
├── notebooks/         # Jupyter demos
├── experiments/       # Hypotheses and results
└── figures/           # Diagrams, illustrations
```

------------------------------------------------------------------------

## 🔹 How to Run Simulations (Classical → Quantum Simulated)

``` bash
# Install environment
pip install qiskit pennylane numpy matplotlib

# Run a 2-qubit entanglement demo
python -m qiskit.circuit.library.XXPlusYYGate
```

------------------------------------------------------------------------

## 🔹 References

-   Michael Nielsen & Isaac Chuang -- *Quantum Computation and Quantum
    Information*\
-   Preskill, J. -- *Quantum Computing in the NISQ era*\
-   Arute et al. (2019) -- *Quantum Supremacy using a programmable
    superconducting processor*\
-   Schuld & Petruccione -- *Machine Learning with Quantum Computers*

------------------------------------------------------------------------

## License

MIT License -- open for research and educational purposes.
