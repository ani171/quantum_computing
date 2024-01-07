# Quantum Computing

## Basics
* **Probabilities**
  * Mutually Exclusive
    1. P(A and B) =0
    2. P(A or B) = P(A) + P(B)
  * Independent
    1. P(A and B)= P(A) x P(B)
    2. P(A or B) = P(A)+ P(B) - P( A and B)
* **Mean** - The mean, often referred to as the average, is a measure of central tendency calculated by adding up all the values in a dataset and then dividing the sum by the total number of values.
* **Median**- The median is the middle value in a sorted dataset. To find the median, the dataset is arranged in ascending or descending order, and the middle value is selected. If the dataset has an even number of values, the median is the average of the two middle values.
* **Variance** - a measure of how much each number in a dataset differs from the mean (average) of the dataset. It is calculated by taking the average of the squared differences between each data point and the mean.
* **Standard deviation** is the square root of the variance. It provides a measure of the average distance between each data point and the mean. A lower standard deviation indicates that the data points tend to be close to the mean, while a higher standard deviation indicates greater dispersion.

![WhatsApp Image 2023-12-30 at 10 34 32 AM](https://github.com/ani171/quantum/assets/97838595/766ca2bb-fc9d-4c63-9a5e-6fbc1f2bc03f)

* **Tensor Product**
  * For two vectors v and w, the tensor product v⊗w results in a matrix. Each element of this matrix is obtained by multiplying the corresponding elements of v and w
![image](https://github.com/ani171/quantum/assets/97838595/c193da07-890b-420d-8c66-cb5ecc6e433b)

* **Unitary Matrix**
  * A unitary matrix is a matrix whose inverse equals its conjugate transpose.
![image](https://github.com/ani171/quantum/assets/97838595/b0c13074-d40f-4cbb-a0d4-6ba9f28e6d61)

* **Hermitian Matrix**
  * A hermitian matrix is a square matrix that is equal to the transpose of its conjugate matrix.
![image](https://github.com/ani171/quantum/assets/97838595/31f080f2-afae-4673-86b8-bf19a0e8d6fa)

## Young's Double Slit Experiment

* Young's double-slit experiment is a fundamental experiment in quantum mechanics that demonstrates the wave-particle duality of particles, such as electrons and photons.
* The experiment involves shining a coherent light source (such as a laser) through a barrier with two closely spaced slits, creating two separate wavefronts. The light then strikes a screen placed some distance away.
* When light passes through the double slits, it creates an interference pattern on the screen. This pattern consists of alternating bright and dark regions, indicating constructive and destructive interference of light waves.
* The interference pattern is a characteristic of the wave nature of light. Waves from the two slits overlap and interfere, creating the observed pattern.
* The interference pattern emerges when particles are not observed, suggesting a wave-like behavior, but when observed, they behave like particles.
* The experiment highlights Heisenberg's uncertainty principle. Knowing which slit a particle passes through disrupts the interference pattern, as determining the path introduces uncertainty in the particle's momentum, affecting its wave-like behavior.

![image](https://github.com/ani171/quantum/assets/97838595/9a844395-cc90-4c64-bf1b-515c003a87eb)

## Electron spin
* Electron spin is a fundamental property of electrons
* Spin is a quantum property, and its behavior is described by quantum mechanics. Unlike classical objects, electrons do not spin in the traditional sense. Instead, they exhibit a form of intrinsic angular momentum.
* Electron spin is associated with a magnetic moment
![image](https://github.com/ani171/quantum/assets/97838595/90bc451f-4eed-4144-9d77-ca4f388c97be)

## Entanglement
* When two electrons are entangled, their properties become linked in a way that the state of one particle directly affects the state of the other
* Before measurement, in the quantum world the particle's properties exist in a superposition state. Via entanglement, when the property of one particle is measured the state of the other is instantly measured

## Qubit
* A qubit, short for a quantum bit, is the fundamental unit of quantum information in quantum computing and quantum information processing.
*  Qubits are the quantum analogs of classical bits. While classical bits can exist in one of two states, 0 or 1, qubits can exist in multiple states simultaneously due to the principles of quantum superposition
![image](https://github.com/ani171/quantum/assets/97838595/68cf49dc-458a-4f8a-9e2a-a2380a80c133)

## Bra-Ket Notation 
* The bra-ket notation is a mathematical notation used in quantum mechanics to represent vectors and linear operators.
* The "ket" is a notation used to represent a quantum state vector. It's denoted by ∣ψ⟩
* The "bra" is the conjugate transpose of the ket. If ∣ψ⟩ is a ket, then ⟨ψ∣ is the corresponding bra.

![WhatsApp Image 2023-12-30 at 11 35 47 AM](https://github.com/ani171/quantum/assets/97838595/84ecae1a-c251-4b5a-90f1-34a7d14a380e)

![image](https://github.com/ani171/quantum/assets/97838595/081baf2c-2130-4b67-adc3-178205418f0b)

#### Multi-qubits
![image](https://github.com/ani171/quantum/assets/97838595/1f715023-081e-4fba-8788-ff0786f371e6)

## Quantum Gates
### X gate
* The X gate, often referred to as the NOT gate, is a fundamental quantum gate in quantum computing. 
* It is analogous to the classical NOT gate, which flips the state of a classical bit.

![WhatsApp Image 2023-12-30 at 11 41 19 AM](https://github.com/ani171/quantum/assets/97838595/411a5a2a-9b20-4890-94cd-78cfda1999fc)

* All qubits start from |0> state unless specified otherwise
![image](https://github.com/ani171/quantum/assets/97838595/c2074029-4307-49aa-a869-0ab489f6a641)
* On putting an X gate in q0
![image](https://github.com/ani171/quantum/assets/97838595/d4de8ec1-90c8-4911-9b5e-236c082a4a2a)
![image](https://github.com/ani171/quantum/assets/97838595/1057722d-3ae5-4651-bca3-17b750d68d0d)
* Multi-qubits
![image](https://github.com/ani171/quantum/assets/97838595/eb64ecb1-708b-45e1-bcf5-b4fe14808f67)
![image](https://github.com/ani171/quantum/assets/97838595/01651a08-4398-49a4-82ff-db258c9ccacc)

### Hadamard Gate
* The Hadamard gate, often denoted as H, plays a crucial role in creating superpositions and is commonly used in various quantum algorithms.
* Makes the qubit go into superposition
![WhatsApp Image 2023-12-30 at 11 57 51 AM](https://github.com/ani171/quantum/assets/97838595/dab36b08-c398-4065-9326-3cd04e7901e1)
![image](https://github.com/ani171/quantum/assets/97838595/365f66d1-ed31-481c-ac1f-12c9034c190e)
![image](https://github.com/ani171/quantum/assets/97838595/9604cc81-6e55-44a8-b664-a2717998fc9f)
* Multi-qubits
  * In here Hadamard gate is put in q[0] alone, thus driving only q[0] into superposition state and not q[1] which is in its |0> state
![image](https://github.com/ani171/quantum/assets/97838595/6180358b-5471-4bd6-9d06-18d673011d6c)

### CNOT Gate
* The Controlled-NOT (CNOT) gate is a fundamental two-qubit gate in quantum computing
* The CNOT gate is commonly used for creating entanglement and implementing quantum algorithms.

![image](https://github.com/ani171/quantum/assets/97838595/90a03c6e-7cb6-416d-b6a1-85390c8eed41)

* The CNOT gate involves two qubits: a control qubit and a target qubit. The operation of the gate depends on the state of the control qubit.
* The first two rows correspond to the cases where the control qubit is in state |0⟩, and the last two rows correspond to the cases where the control qubit is in state |1⟩.
* If the control qubit is in state |0⟩, the CNOT gate performs the identity operation on the target qubit (leaves it unchanged)
* If the control qubit is in state |1⟩, the CNOT gate flips the state of the target qubit (applies an X gate)

### Hadamard and CNOT gate 
* Applying a Hadamard gate and a CNOT gate together on a pair of qubits is a common operation in quantum computing. This combination is often used to create entanglement
![image](https://github.com/ani171/quantum/assets/97838595/cf63760f-dd5a-4bb0-82ff-2d7dcc0d7b4c)
* Here is how it is done
![image](https://github.com/ani171/quantum/assets/97838595/c1aa78e8-3d7c-46b5-92a8-f4aa3e7933bd)

![image](https://github.com/ani171/quantum/assets/97838595/6aea77c0-0b6b-48ed-93ea-425ebe0a851a)

### Toff0li gate
* The Toffoli gate is a three-qubit gate in quantum computing.
* also known as the Controlled-Controlled-NOT (CCX) gate
* The Toffoli gate performs a NOT (X) operation on a target qubit only if both control qubits are in the state ∣1⟩.
![image](https://github.com/ani171/quantum_computing/assets/97838595/e4e588dc-3db5-434d-98c9-c05987d81144)
![image](https://github.com/ani171/quantum_computing/assets/97838595/21aae26b-e22f-44cc-8d65-0d9b6a2a5727)
* In below only q0 is made |1> thus no change in q2
![image](https://github.com/ani171/quantum_computing/assets/97838595/1b1d066a-4341-4709-be92-82a15cc5c34c)
* As both controls that is q0 and q1 are 1 so q2's initial value is reversed ---> |111>
![image](https://github.com/ani171/quantum_computing/assets/97838595/cb42b080-e7d2-4a90-872e-3dfd49a6f5e3)

### Z gate
* also known as the phase gate or Z-Pauli gate
* a single-qubit quantum gate that introduces a phase shift to the qubit state
![image](https://github.com/ani171/quantum_computing/assets/97838595/026f2070-0894-4c5d-a848-5a1973effa17)
*
  * Z |0> = |0>
  * Z |1> = |-1>
![WhatsApp Image 2023-12-30 at 6 22 22 PM](https://github.com/ani171/quantum_computing/assets/97838595/dac851d4-4e55-4c6d-abad-cfdf2bd70c59)
* A phase pi can be observed below, but the outcome isn't affected ( but it is not that Z gate doesn't affect the computation probability)
![image](https://github.com/ani171/quantum_computing/assets/97838595/935c0a4c-65b8-43eb-8242-68bba7469dff)

## Qiskit
[Qiskit](qiskit)

## Teleportation
[Teleportation]()
