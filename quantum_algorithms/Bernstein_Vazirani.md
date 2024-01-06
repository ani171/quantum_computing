# Bernstein Vazirani

1. Problem Statement:
    * There is a hidden binary string (a sequence of 0s and 1s) that we want to discover.
    * For example, the hidden string could be something like '101010'.
2. Classical Approach:
    * In classical computing, to find the hidden string, we would need to ask multiple questions (queries).
    * We might ask, "Is the first digit 0?" If yes, move to the second digit, and so on.
    * This requires asking multiple questions to pinpoint each bit of the hidden string.
3. Quantum Advantage:
    * The Bernstein-Vazirani algorithm is a quantum algorithm that provides a significant speedup for this specific problem.
    * It can find the hidden string with just one query, regardless of the length of the string.
4. Quantum Magic:
    * The algorithm uses quantum gates, particularly Hadamard gates and controlled-X (CNOT) gates, to perform operations on qubits.
    * It initializes a set of qubits and prepares them in a superposition state using Hadamard gates.
5. Oracle Function:
    * The algorithm utilizes a quantum oracle function that encodes the hidden binary string into the quantum state.
    * This oracle function is implemented using controlled-X (CNOT) gates.
6. Measurement:
    * The algorithm then applies Hadamard gates again and measures the qubits.
    * The measurement outcomes provide the hidden binary string directly.
7. Quantum Parallelism:
    * The quantum advantage comes from the ability of quantum bits to exist in multiple states simultaneously (superposition).
    * The algorithm explores all possible states in parallel, making it efficient for certain problems like finding a hidden binary string.
8. Conclusion:
* The Bernstein-Vazirani algorithm is a powerful demonstration of how quantum computing can outperform classical approaches for specific tasks, showcasing the unique advantages of quantum parallelism.
