# CSCI-739 Quantum Machine Learning

Course materials for CSCI-739 (Topics in Artificial Intelligence: Quantum Machine Learning) at the Rochester Institute of Technology, taught by Dr. Ryan Vogt.

The course looks at where machine learning and quantum computing meet. We start with how classical ML is already used in quantum computing research and what today's noisy (NISQ) hardware can and cannot do. From there we cover how classical data gets loaded into quantum states, variational circuits, quantum kernels and support vector machines, quantum neural networks, quantum Boltzmann machines, and quantum generative models. Throughout, the question is not only how these methods work but when, if ever, they give a real advantage over classical methods.

## What's in this repository

| Folder | Contents |
|---|---|
| `slides/` | Lecture slides (PDF, typeset in LaTeX/Beamer) |
| `Getting started with Qiskit & QuTiP/` | Two introductory Jupyter notebooks: Qiskit (including running on IBM Quantum hardware) and QuTiP |
| `Homework 1/` ... `Homework 5/` | Each assignment as a PDF, with its LaTeX source (`main.tex`) and figures |

## Lectures

| # | Slides | Topic |
|---|---|---|
| 1 | [01_Classical_ML_Meets_Quantum_Computing.pdf](slides/01_Classical_ML_Meets_Quantum_Computing.pdf) | Classical machine learning meets quantum computing |
| 2 | [02_Qubits_Ecosystem_and_NISQ.pdf](slides/02_Qubits_Ecosystem_and_NISQ.pdf) | Qubit properties, the quantum computing ecosystem, NISQ computers and what they mean for QML |
| 3 | [03_Classical_ML_in_Quantum_Computing_Research.pdf](slides/03_Classical_ML_in_Quantum_Computing_Research.pdf) | Classical machine learning in quantum computing research |
| 4 | [04_Quantum_Encoding_of_Classical_Data.pdf](slides/04_Quantum_Encoding_of_Classical_Data.pdf) | Encoding classical data into quantum states |
| 5 | [05_Variational_Quantum_Algorithms.pdf](slides/05_Variational_Quantum_Algorithms.pdf) | Variational quantum algorithms (circuits) |
| 6 | [06_Quantum_SVMs_and_Kernel_Methods.pdf](slides/06_Quantum_SVMs_and_Kernel_Methods.pdf) | Quantum support vector machines and kernel methods |
| 7 | [07_Quantum_Neural_Networks.pdf](slides/07_Quantum_Neural_Networks.pdf) | Quantum neural networks |
| 8 | [08_Quantum_Boltzmann_Machines.pdf](slides/08_Quantum_Boltzmann_Machines.pdf) | Quantum Boltzmann machines |
| 9 | [09_Quantum_GANs_Transformers_AGI_and_QAGI.pdf](slides/09_Quantum_GANs_Transformers_AGI_and_QAGI.pdf) | Quantum GANs and transformers, AGI and QAGI |

Each deck ends with an optional supplementary section: a deeper dive on the topic, papers worth reading first, books and courses, and open questions that could become thesis or project ideas.

## Getting started

Before the first homework, work through the two notebooks in `Getting started with Qiskit & QuTiP/`. The Qiskit notebook covers building and simulating circuits and connecting to IBM Quantum computers (you will need your own free IBM Quantum account and API token). The QuTiP notebook introduces QuTiP's quantum objects, states, density matrices and operators.

## Homework

| | Topics | Points |
|---|---|---|
| [Homework 1](Homework%201/QuantumMLHW1.pdf) | Quantum computing foundations for QML: qubits and measurement, two-qubit systems and CNOT, the Bloch sphere and single-qubit gates, tensor products and circuits, a ripple-carry adder in Qiskit. Bonus: the time-dependent Schrödinger equation, and adding 2+2 on a quantum computer. | 100 + 30 bonus |
| [Homework 2](Homework%202/QuantumMLHW2.pdf) | From noisy primitives to scalable QML: noisy Hadamard gates, logical error rates for QML workloads under the surface code, encoding π and e (basis, amplitude and angle encodings), and Bell-state circuit synthesis with reinforcement learning. Bonus: analytic Lindblad solutions, and preparing π in Qiskit. | 100 + 50 bonus |
| [Homework 3](Homework%203/QuantumMLHW3.pdf) | Variational circuits and kernels: a phase-deformed X gate, finding a ground state analytically and with a VQC, the XOR problem and encoding strategies, and a quantum SVM for XOR. Bonus: theory of variational circuits. | 100 + 25 bonus |
| [Homework 4](Homework%204/QuantumMLHW4.pdf) | Quantum neural networks. Either two problems (expressivity and universal approximation; classical vs. quantum networks on a sine function) or a quantum MNIST project on encodings, PCA and what is realistically doable. Bonus: diagonal Hamiltonian ground states, the complexity of state preparation, and multivariate sine regression. | 100 + 50 bonus |
| [Homework 5](Homework%205/QuantumMLHW5.pdf) | Optional bonus assignment: guided reading of four papers (QAOA, quantum algorithms for nonlinear PDEs, binary optimal control of single-flux-quantum pulses, and decoded quantum interferometry), with the papers included in the folder. | Bonus |

## Final project

Students propose a project (individually or in a small group), carry it out over the second half of the semester, and present it in the final class meetings.

## Contact

Dr. Ryan Vogt, rhvvcs@rit.edu
