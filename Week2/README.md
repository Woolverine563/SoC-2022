**_Week 2_** involved reading up on the sections of QCQI involving:

1) The representation of qubit states on the **Bloch sphere**
2) The basics of Quantum Circuits
3) The implementation of any **controlled-Unitary** gate using single qubit gates and the CNOT gate
4) The concept of a gate controlled by n qubits and its implementation
5) The **universality** of the _CNOT, T, Phase and H_ gates for Quantum computation
6) **Measurement Principles** in Quantum Circuits

The coding part of this week was done using the Qiskit package.

As part of this, we were introduced to:
1) The basics of Qiskit by trying to simulate the 4 Bell states and general GHZ states.
2) The _Deustch-Jozsa_ Algorithm which uses the superposition of quantum states to classify a Quantum Oracle as balanced or constant.
3) The _Bernstein-Vazirani_ Algorithm which involves finding a string used by a function Oracle.
4) Quantum Teleportation which allows the communication of 2 real numbers with precision using only 2 bits of communication. This uses the principle of Quantum **Entanglement** and collapse (_projection onto an eigenspace_) of an entangled system on Measurement.
5) Superdense coding which uses similar conceps to **safely** transmit a 2-bit string using a single qubit.
6) Logic used in Quantum Circuits by trying to simulate **+, <, ++** operations modulo 8 with 3-qubit systems.
