# Qiskit

* Qiskit is an open-source quantum computing software development framework developed by IBM.
* It provides tools for working with quantum circuits, simulating quantum algorithms, and accessing IBM's cloud-based quantum processors.
* Qiskit is designed to make it easy for users to interact with quantum computers and develop quantum applications.

## Components of Qiskit
1. Terra:
  * Think of Terra as the foundation or building blocks of Qiskit. It's like the toolbox that helps you construct, optimize, and run quantum circuits. With Terra, you can easily create and manipulate quantum circuits using a user-friendly programming language.
2. Aer:
  * Aer is like a powerful simulator within Qiskit. It allows you to test and play around with your quantum circuits on a regular computer. You can simulate how a quantum computer would behave without actually needing access to one. Aer includes different simulation methods to analyze and debug your quantum algorithms.
3. Ignis:
  * Ignis is the part of Qiskit that focuses on dealing with mistakes and errors that might happen when using a quantum computer. It provides tools to understand and reduce errors in your quantum circuits. It's like having a guide that helps you navigate and correct issues, making your quantum computations more reliable.
4. Aqua:
  * Aqua is like a library of ready-to-use quantum applications. It contains various quantum algorithms for different purposes, like solving finance problems, optimizing solutions, machine learning, and working with chemistry-related challenges. It's a set of tools and solutions that you can directly apply to real-world problems using quantum computing.
5. Providers:
  * Qiskit allows users to run their quantum circuits on real quantum processors through cloud-based providers. IBM Quantum is one such provider, and users can access their quantum devices remotely.

## Installation
* You can install Qiskit using Python's package manager, pip
`pip install qiskit`
![image](https://github.com/ani171/quantum/assets/97838595/f2f98271-11fe-4baa-ae43-21a17b944a1a)

* Or use qiskit using IBM's quantum lab

## Quantum noise
* Quantum noise refers to the inherent uncertainty and randomness that arises in quantum systems.
* It is a fundamental aspect of quantum mechanics and is distinct from classical noise.

1. Decoherence:
  * Quantum systems are inherently susceptible to decoherence, where quantum information can be lost to the environment. Real quantum devices experience decoherence, causing the degradation of quantum states over time.
2. Gate Errors:
  * Physical qubits and quantum gates in real devices may have imperfections, leading to errors in quantum operations.
3. Readout Errors:
  * When measuring a quantum state, readout errors can occur. These errors lead to discrepancies between the intended measurement outcome and the observed result.
4. Crosstalk:
  * Crosstalk refers to unintended interactions between qubits. Quantum computers consist of multiple qubits, and operations on one qubit can potentially influence neighboring qubits, leading to unwanted correlations and errors.
5. Thermal Noise:
  * Temperature fluctuations in the environment can introduce thermal noise, affecting the stability of qubits and their susceptibility to external influences.
6. Quantum Fluctuations:
  * Quantum systems are subject to inherent fluctuations due to the uncertainty principle. These fluctuations introduce probabilistic variations in quantum states, contributing to the overall quantum noise.

* Output of qasm_simulator 
![image](https://github.com/ani171/quantum/assets/97838595/479038db-dadf-4d92-9fbe-a992f08d75fa)

* Output of ibqm simulator (here ibqm_kyoto)
![image](https://github.com/ani171/quantum/assets/97838595/f2669ecb-6795-4b71-aa39-9c39ef7dcb8f)
  * A noise can be observed at <01| and <10|
  * The Qiskit Aer qasm_simulator is a simulator that provides an idealized representation of quantum circuits, meaning it does not model certain types of errors or noise that are present in real-world quantum devices. This is intentional and designed to allow users to simulate quantum circuits without the complicating effects of noise, decoherence, and other imperfections
  *  When you run your quantum circuits on actual quantum hardware or use more realistic simulators like the ibmq_simulator (which simulates the noise characteristics of IBM Quantum devices), you start to encounter quantum noise due to various factors
