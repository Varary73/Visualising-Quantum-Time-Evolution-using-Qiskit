# Visualising Quantum Time Evolution using Qiskit
Visualising the quantum time evolution by simulating a Hamiltonian using the Split Operator Fourier Transform Algorithm in Qiskit

## (In focus) Quantum tunnelling effect

### Team
1. Vardaan Sahgal
2. Ashly Martinez Rodriguez
3. Havishvarma Vinodchandran

### Problem Statement
A quantum mechanical phenomenon in which a wave function can propagate across a potential barrier is known as quantum tunnelling. One of several possible scenarios in which we can witness the evolution of quantum operators over time. The transmission through the barrier can be finite and is proportional to the height and width of the barrier. On one side of the barrier, the wave function vanishes and resurfaces on the other. 

In a physical phenomenon such as nuclear fusion, quantum tunnelling is critical. It has uses in the scanning tunnelling microscope, quantum computer hardware, and tunnel diodes. One of the mechanisms of proton decay could be quantum tunnelling. Because electrons can tunnel beyond transistors that are too small, quantum tunnelling is expected to put physical constraints on the size of transistors used in microelectronics. Therefore, simulation of the quantum tunnelling phenomenon or quantum time evolution, in general, is a significant problem, which if solved could lead to a plethora of industrial use cases.

### Our Solution
Quantum tunnelling is not predicted by the Laws Of Classical Mechanics, where surmounting a potential barrier requires potential energy. Thus, this provides us with an exciting opportunity to try and simulate the phenomenon using Quantum computers, which inherently use quantum physics. Our solution uses the Split operator Fourier transform algorithm to simulate the Quantum tunnelling phenomenon in Qiskit.

In our proposed solution, we started with the time-evolution wave function of a quantum particle. The hamiltonian of our system is broken down and split into an infinite amount of smaller steps alternating between kinetic and potential propagators using the Lie-Trotter product formula. We initialized the wave function discretized into 2^N grid points where N is the number of qubits (excluding ancillary) used in the circuit. Following this, we applied the potential operator the Quantum Fourier Transform (QFT), the kinetic operator, and the inverse QFT, in the desired number of iterations. The circuit is then measured and represented as a histogram, which gives us a clear visualization of the Quantum-tunneling phenomenon.

After understanding the fundamentals of using the split operator approach to simulate one particle moving, the next step is to investigate particle interactions and chemical dynamics, which has tremendous research applications in domains. Such as drug development, condensed matter physics, and material science.

### Presentation
[Presentation Link @ Google Slides](google.com)
</br>
[Video Presentation](youtube.com)

### References
https://fount.aucegypt.edu/cgi/viewcontent.cgi?article=1020&context=capstone
https://youtu.be/7Bsx_4hOU3g
https://youtu.be/o96K8fkOrG8
https://qiskit.org/textbook-beta
http://www.science4all.org/article/dynamics-of-the-wave-function/
