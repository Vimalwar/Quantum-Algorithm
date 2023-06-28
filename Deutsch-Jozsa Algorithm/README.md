The Deutsch-Jozsa algorithm is a quantum algorithm, proposed by David Deutsch and Richard Jozsa in 1992. It was one of first examples of a quantum algorithm, which is a class of algorithms designed for execution on Quantum computers and have the potential to be more efficient than conventional,
classical, algorithms by taking advantage of the quantum superposition and entanglement principles.

In Deutsch-Jozsa problem, we are given a black box computing a 0-1 valued function f(x1, x2, ..., xn). The black box takes n bits x1, x2, ..., xn and outputs the
value f(x1, x2, ..., xn). We know that the function in the black box is either constant (0 on all inputs or 1 on all inputs) or 
balanced (returns 1 for half the domain and 0 for the other half). The task is to determine whether f is constant or balanced.

The algorithm is as follows. First, do Hadamard transformations on n 0s, forming all possible inputs, and a single 1, which will be the answer qubit. 
Next, run the function once; this XORs the result with the answer qubit.
Finally, do Hadamards on the n inputs again, and measure the answer qubit. If it is 0, the function is constant, otherwise the function is balanced.
