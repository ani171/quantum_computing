# Deutsch-Josza Algorithm

* We're given a mysterious function f(x) that takes a binary input (x) and gives a binary output.
* We want to figure out if this function is either:
    * Constant: It always gives the same output, whether 0 or 1.
    * Balanced: It gives an equal number of 0s and 1s for different inputs.
* Classically, to determine if a function is constant or balanced, you would need to evaluate the function for multiple inputs.
* The Deutsch-Josza algorithm is a quantum algorithm that can solve this problem in just one query to the function, providing a speedup over classical approaches.
* It uses quantum parallelism and interference to efficiently evaluate the function.
* It involves a quantum oracle that implements the function f(x) using specific quantum gates.
* The algorithm starts with n+1  qubits initialized in the state |0>|1>
* Applies Hadamard gates to create a superposition of all possible input states.
* Applies the quantum oracle that performs
![image](https://github.com/ani171/quantum_computing/assets/97838595/bb8d81b3-bef3-4dbe-a44f-78fe8f70ad54)
* Applies Hadamard gates again to amplify the probability of measuring the solution.
* Measures the first n qubits. If the measurement result is all zeros, the function is constant. If it's any other binary string, the function is balanced.


![image](https://github.com/ani171/quantum_computing/assets/97838595/aa091501-e6b7-48b2-bf5b-5bd964a8a3ae)

![image](https://github.com/ani171/quantum_computing/assets/97838595/463ebecb-c0b7-4178-aa17-9611aeb5e930)

