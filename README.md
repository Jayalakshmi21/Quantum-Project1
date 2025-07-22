# Quantum Computing Examples with Qiskit

This repository contains Jupyter notebook examples demonstrating quantum computing concepts using Qiskit, including Bell states, GHZ states, and Grover's algorithm.

## Project Structure

- [`helloworld.ipynb`](helloworld.ipynb) - Hello World example demonstrating 2-qubit Bell state and n-qubit GHZ state
- [`Grover's Algorithm for Database Search.ipynb`](Grover's%20Algorithm%20for%20Database%20Search.ipynb) - Implementation of Grover's algorithm for quantum database search
- [`hydrogen.ipynb`](hydrogen.ipynb) - Quantum chemistry example
- [`hi.ipynb`](hi.ipynb) - Additional quantum examples
- [`install-1.ipynb`](install-1.ipynb) - Installation and setup guide
- [`resume-parser/`](resume-parser/) - Collection of PDF resumes (auxiliary files)

## Main Examples

### Hello World - Bell State and GHZ State

The [`helloworld.ipynb`](helloworld.ipynb) notebook demonstrates:

1. **2-Qubit Bell State Creation**
   - Creates a quantum circuit with 2 qubits
   - Applies Hadamard gate and CNOT gate
   - Measures expectation values of various Pauli operators

2. **N-Qubit GHZ State**
   - Extends the concept to 100-qubit GHZ states
   - Demonstrates quantum circuit optimization
   - Executes on real quantum hardware using IBM Quantum
   - Includes post-processing and visualization

### Key Features

- **Quantum Circuit Creation**: Using Qiskit's `QuantumCircuit`
- **Quantum Operators**: Working with Pauli operators and SparsePauliOp
- **Hardware Execution**: Running on IBM Quantum backends
- **Optimization**: Circuit transpilation and optimization
- **Error Mitigation**: Resilience levels and dynamical decoupling
- **Visualization**: Plotting expectation values and quantum states

## Prerequisites

- Python 3.7+
- Qiskit
- Qiskit Runtime
- Qiskit Aer
- Matplotlib
- Jupyter Notebook

## Installation

Refer to [`install-1.ipynb`](install-1.ipynb) for detailed installation instructions.

## Usage

1. Open any of the Jupyter notebooks
2. Run the cells sequentially
3. For hardware execution, ensure you have IBM Quantum account credentials configured

## Quantum Algorithms Included

- **Bell State Preparation**: Fundamental quantum entanglement example
- **GHZ State**: Multi-qubit entangled states
- **Grover's Algorithm**: Quantum database search algorithm
- **Quantum Chemistry**: Hydrogen molecule simulation

This project serves as an educational resource for learning quantum computing concepts and practical implementation using Qiskit.
