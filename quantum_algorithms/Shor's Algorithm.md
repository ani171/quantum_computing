# Shor's Algorithm

### Classical Factorization
* Problem:
    * Given a large number N, the task is to find its prime factors.
* Classical Approach:
    * Classically, the best-known algorithms have exponential complexity, meaning they become very slow as the number N grows.
    * Factorization of large numbers becomes impractical and time-consuming with classical methods.

### Quantum way

* It utilizes quantum parallelism and interference to explore multiple possibilities simultaneously.
* A key component is the Quantum Fourier Transform, which efficiently processes information in quantum superposition.
    * In quantum computing, QFT generalizes the classical Fourier Transform to work with quantum superpositions.
    * QFT operates on a quantum state represented by a set of qubits.
    * Each qubit corresponds to a different frequency.
    * QFT transforms a quantum state by changing the amplitudes of basis states based on their frequency.
    * The construction involves a series of Hadamard gates and controlled-phase gates.
    * The Hadamard gates create superposition, putting the qubits in a state of all possible combinations.
    * Controlled-Phase gates introduce phase shifts based on the frequency of each qubit.
    * QFT amplifies the amplitudes of states with higher frequencies.
* Shor's procedure
    * Pick a random number a smaller than N.
    * Select a random integer a such that 1<a<N. This random number a is crucial for the algorithm and helps in finding the period of a modular exponentiation function.
    * Find the smallest positive integer r such that a<sup>r</sup>|N| =1
    * Shor's algorithm uses quantum operations, including Quantum Fourier Transform, to efficiently explore possibilities in parallel.
    * Quantum algorithms excel at finding periodicity efficiently, a task that would be classically time-consuming for large numbers.
    * If r is even and a<sup>r/2</sup> =! -1 |N|
        * Determine if the period r satisfies certain conditions.
        * the factors of N can be computed efficiently.
    
