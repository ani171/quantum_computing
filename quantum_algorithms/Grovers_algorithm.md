# Grover's algorithm

### Classical search

* Imagine you have an unsorted database, and you need to find an item with a specific property.
* Classical Approach:
    * In classical computing, you'd typically need to check each item one by one until you find the right one.
    * The worst-case scenario is searching half of the database on average.

### Quantum search

* We still have an unsorted database, but Grover's algorithm aims to find the item much faster.
* Grover's algorithm uses superposition and interference, two key quantum concepts.
* It operates on a quantum state representing all possible items simultaneously.
* Grover's Procedure:
      1. Initialization:
            * All possible items are put into a superposition.
            * Apply a Hadamard transform to create an equal superposition.
      2. Oracle:
            * Use a quantum oracle to mark the solution(s) (the item(s) with the desired property).
      3. Amplitude Amplification:
            * Apply a series of quantum operations to amplify the amplitude of the marked state(s) and reduce others.
            * This involves the application of the oracle and a diffuser.
      4. Iteration:
            * Repeating the oracle and amplitude amplification steps a specific number of times (approximately root(N) times, where N is the number of items).
* Grover's algorithm has a quadratic speedup over classical search algorithms.
* Classically, you might need to check N/2 items on average, while Grover's algorithm can find the item in approximately root (N) steps.

​
