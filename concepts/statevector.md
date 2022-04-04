## The Quantum Statevector

The quantum statevector is a vector of complex numbers, where each element represents the probability of a particular state.
Quantum Simulators use the statevector to represent the Quantum System at a particular point during the circuit's computation.
Beginning in the initial state, the vector is multiplied by the matrix of the current gate, and the resulting vector is the statevector's next state in the computation.


The statevector approach is also the limiting factor in our ability to simulate quantum circuits on classical machines, since we need to store each state of the quantum circuit in memory. 
The size of the statevector is `2^N`, where `N` is the number of qubits in the quantum circuit.
That is to say, your laptop may be able to simulate a quantum circuit with `N=32` qubits, but it may not be able to simulate a quantum circuit with `N=64`. Useful applications may require hundreds of thousands of qubits, which would require a statevector of `2^100` elements.

In a Quantum Computer, the statevector is represented by the state of the Quantum System itself, and the final values are measured on an as-needed basis.