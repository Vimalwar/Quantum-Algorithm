"Grover's Algorithm" is a quantum algorithm that can search an unstructured database of N items in O(sqrt(N)) time. 
This is an exponential speedup over classical algorithms, which require O(N) time. 
Grover's Algorithm uses amplitude amplification to amplify the probability of finding the correct item, shrinks the other items' amplitude
allowing for faster searching.

Grover's algorithm has three main components.

1. First, we begin by creating a superposition of all  2𝑛 computational basis states by applying a Hadamard ( 𝐻 ) gate on each qubit starting off in the state
 |0⟩⊗𝑛. Here, the exponent  ⊗𝑛 means that we have a tensor product of the states of  𝑛 qubits.
2. Second, we apply an Oracle operator to mark the appropriate elements among the  2𝑛 elements. The oracle operator applies a coefficient of  −1
  to each of the marked elements.
3. Third, we apply a Diffusion operator, or diffuser, which inverts the amplitude of all elements about the average amplitude.
