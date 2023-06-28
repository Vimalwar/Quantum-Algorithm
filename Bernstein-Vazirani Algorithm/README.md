The Bernstein-Vazirani algorithm can be seen as an extension of the Deutsch-Josza algorithm.
It shows that there can be advantages in using a quantum computer as a computational tool for more complex problems,
Quantum computing can go far beyond the possibilities of today’s classical high performance computing.

Given a black box function f, which takes as input a string of bits x and outputs the inner product of x with a hidden binary string s 
(i.e., the bitwise AND of x and s modulo 2), the goal is to determine the hidden string s. In other words, we want to find the secret binary string 
that the function f is based on.

With classical computer very time we can perform a single and operation on box and see the output result and finally get to know the number.
But with a Quantum computer and by using Bernstein-Vazirani Algorithm we can know the number just with on operation.

In order to implement Bernstein-Vazirani Algorithm, we need to take few steps:

1. Initialise the inputs qubits to the |0> state, and output qubit to |->.

2. Apply Hadamard gates to the input register

3. Query the oracle

4. Apply Hadamard gates to the input register

5. Measure
