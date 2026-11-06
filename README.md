### Using Schmidt Decomposition and Entanglement Entropy with Qiskit-Based Quantum Circuit Simulation

## 📌 Overview

Quantum entanglement is one of the fundamental properties of quantum mechanics, where two or more quantum systems exhibit correlations that cannot be explained by classical physics.

This project explores the **generation, mathematical representation, and quantification of bipartite quantum entanglement** using Schmidt decomposition and entanglement entropy.

The project combines mathematical analysis with quantum circuit simulation using **Python and Qiskit** to study and compare product, partially entangled, and maximally entangled two-qubit states.

## 🎯 Objectives

- Understand bipartite quantum states and their mathematical representation.
- Implement Schmidt decomposition using Singular Value Decomposition (SVD).
- Calculate Schmidt coefficients and Schmidt rank.
- Quantify entanglement using von Neumann entropy.
- Generate quantum states using Qiskit quantum circuits.
- Compare product, partially entangled, and maximally entangled states.
- Investigate how entanglement changes with the rotation parameter of a quantum circuit.

## 📊 Experiments and Visualizations

The project includes:

1. Quantum circuit diagrams for all three states.
2. Statevector extraction using Qiskit.
3. Schmidt coefficient calculation using NumPy SVD.
4. Schmidt rank comparison.
5. Entanglement entropy calculation.
6. Bar graph comparing entanglement entropy across the three states.
7. Entanglement entropy versus rotation angle.

The parameter-based experiment demonstrates how entanglement increases as the rotation angle changes from \(0\) to \(\pi/4\).

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming and numerical analysis |
| Qiskit | Quantum circuit construction and simulation |
| NumPy | Matrix operations and SVD |
| Matplotlib | Data visualization |
| Google Colab | Cloud-based development environment |

## 🚀 Getting Started

### Option 1: Run on Google Colab

Open the project notebook in Google Colab and execute the cells sequentially.

### Option 2: Run Locally

Clone the repository:

```bash
git clone https://github.com/arc03/Quantum_Entanglement.git
cd your-repository-name
```

Install the required libraries:

```bash
pip install qiskit numpy matplotlib pylatexenc
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook and run the cells.

## 📁 Project Structure

```text
Bipartite-Quantum-Entanglement/
│
├── Computational_Analysis_of_Bipartite_Quantum_Entanglement.ipynb
│
├── README.md
│
└── outputs/
    ├── quantum_circuits/
    └── graphs/
```

*The outputs directory is intended for saved circuit diagrams and experimental plots.*

## 🔍 Key Observations

- A product state has Schmidt rank 1 and zero entanglement entropy.
- A partially entangled state has Schmidt rank 2 and entropy between 0 and 1 bit.
- A Bell state has Schmidt rank 2 and maximum entanglement entropy of 1 bit.
- Schmidt rank identifies whether a pure bipartite state is entangled, while entanglement entropy quantifies the degree of entanglement.
- The quantum circuit simulation and mathematical SVD-based analysis provide two complementary ways to investigate entanglement.

## 🌐 Applications of Quantum Entanglement

Quantum entanglement is an important resource in several quantum technologies, including:

- Quantum communication and quantum key distribution.
- Quantum teleportation.
- Superdense coding.
- Quantum computing.
- Quantum networks and quantum information processing.

## 📚 References

1. Nielsen, M. A., and Chuang, I. L., *Quantum Computation and Quantum Information*, Cambridge University Press.
2. Qiskit Documentation: https://docs.quantum.ibm.com/
3. NumPy Documentation: https://numpy.org/doc/
4. Matplotlib Documentation: https://matplotlib.org/

---

*This project is an educational and computational study of bipartite quantum entanglement using mathematical methods and quantum circuit simulation.*
