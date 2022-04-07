## Simulating Quantum Computers


Quantum Computers can be simulated on classical machines by representing a quantum system using a [statevector](./statevector.md) and evolving it by performing a matrix multiplication on the statevector against each of the quantum gates.

### Limitations 
Unfortunately, our ability to simulate quantum computers is limited by the statevector's size growing exponential with the number of qubits in the system, specifically: `2^n`, where `n` is the number of qubits in the system.


### References
- [Simulating Quantum Computers with Qiskit](https://qiskit.org/documentation/tutorials/simulators/1_aer_provider.html)
- [IBM Quantum Simulators](https://www.ibm.com/quantum-computing/simulator/)
- [Quantum Simulators](https://en.wikipedia.org/wiki/Quantum_simulator)
- [Limitations of Simulating Quantum Circuits](https://link.aps.org/doi/10.1103/PhysRevX.10.041038)
