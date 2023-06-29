# NULLPUL

NULLPUL is a project that explores the benefits of utilizing higher energy states in quantum computation using Qiskit Pulse.

## Description

Quantum computers operate on different sets of physical laws compared to classical computers. One consequence of this is the phenomenon of interference, where constructive and destructive interference can occur. By harnessing interference in a quantum circuit, we can achieve constructive interference for correct answers and destructive interference for wrong answers, effectively nullifying the undesired outcomes.

Qiskit Pulse provides a powerful tool to program real quantum computers at the pulse level, allowing us to control the continuous-time dynamics of input signals. While most quantum algorithms operate within the 2^n-dimensional Hilbert space spanned by {|0>,|1⟩}^n, IBM's quantum hardware also allows exploration of higher energy states that are typically avoided, such as the |2> state. By leveraging Qiskit Pulse, we can investigate these higher energy states and demonstrate their direct benefits in quantum computation.

## Installation

To use NULLPUL and run the code examples, you'll need to have the following prerequisites:

- Python 3.7 or later
- Qiskit 0.32.0 or later
- IBM Quantum Experience account

