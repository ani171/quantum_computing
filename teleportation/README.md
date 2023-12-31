# Teleportation
* Quantum teleportation is a quantum communication protocol that allows the transfer of the state of a quantum system from one location to another with the help of two entangled particles and classical communication.
* quantum teleportation doesn't involve the physical transportation of particles; instead, it transfers the information contained in a quantum state from one location to another

## Bloch sphere
* The Bloch sphere is a geometric representation of the state space of a single qubit in quantum mechanics.
* It provides a convenient way to visualize and understand the quantum states of a qubit.
* The surface of the Bloch sphere represents all possible states of a qubit, while points within the sphere represent superpositions of those states.

## Superdense coding
* Superdense coding is a quantum communication protocol that enables two parties to communicate two classical bits of information by exchanging only one qubit.

### Simple terms
1. Alice and Bob each have one special qubit. These qubits are entangled
2. Alice wants to send a secret two-bit message. She operates (applies gates) on her qubit based on the message she wants to send. The entanglement ensures that any change Alice makes to her qubit instantly affects Bob's qubit.
3. Alice sends her qubit to Bob
4. Bob receives Alice's qubit. He performs another special operation involving both qubits. This operation lets him figure out the secret two-bit message encoded by Alice's operation

### Bell pair
* Also known as EPR pairs (named after Einstein, Podolsky, and Rosen)
* A Bell pair is a pair of qubits that are entangled in such a way that the quantum states of the two qubits are correlated, regardless of the physical separation between them.
* The most common type of Bell pair is created using the Hadamard gate (H) and the Controlled NOT gate
* Creation of a Bell pair
    1. Start with two qubits initially in the ∣0⟩ state
    2. Apply a Hadamard gate to the first qubit. This puts the first qubit into a superposition state.
    3. Apply a CNOT gate, where the first qubit is the control qubit, and the second qubit is the target qubit.
    4.  Resultant would be
![image](https://github.com/ani171/quantum_computing/assets/97838595/3d1c2d23-0d2b-44f2-acf0-e8d1e0de710e)
![image](https://github.com/ani171/quantum_computing/assets/97838595/891385d6-7735-431d-be28-a022a654af2e)
* In here Bell pair is created on both sides by applying the Hadamard gate and CNOT gate
* Now if Allice wants to send |00> to Bob, she applies an I gate on q0 bit
* Similarly to send |10> she applies a X gate for |01> a Z gate and for |11> a XZ gate
* Note that Allice performs operations only on q0 bit
* Now once Bob receives the encoded message, he puts a CNOT and Hadamard gate to decode the sent message
1. Creation of Bell pair
![image](https://github.com/ani171/quantum_computing/assets/97838595/a20d8f3d-d7e5-4250-b15d-d17fc17f98cd)
2. For 00 transmission, Allice applies an I gate on q0
![image](https://github.com/ani171/quantum_computing/assets/97838595/36ed9f85-275e-4948-b4fd-8c5d1f52aac5)
3. For 01 transmission
![image](https://github.com/ani171/quantum_computing/assets/97838595/b65feb14-61ed-4244-89a3-486607294161)
4. For 10 transmission
![image](https://github.com/ani171/quantum_computing/assets/97838595/6199b1f7-89b7-427a-821b-6b7acba39b0a)
5. For 11 transmission
![image](https://github.com/ani171/quantum_computing/assets/97838595/917bc167-86fa-49b7-9295-145674e4e16c)

