# GroverSearch
Quantum Programming

Grover’s algorithm is a solution to the unstructured search problem. Using a classical computer, the solution to this problem is O(n), using grover’s algorithm it is O(n )

1. We begin by create a superposition of all n possibilities/elements
2. We apply an oracle function which marks the state containing the “correct” variable. The oracle flips the sign of the amplitude of marked states.
3. We then apply a diffusion/Grover operator, which amplifies the amplitudes of the states that correspond to our goal. It does via iterative application and does 2 things: reflects about the mean and the inversion of the marked state. 
4. We then measure the state of the system, which collapses the superposition and returns the highest amplitude.

I completed this exercise as a practise in quantum programming following my certification in the black opal quantum course.
