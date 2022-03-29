# Quantum-Reinforcement-Learning
Master Thesis project at Politecnico di Torino. Work done under the supervision of professor [Davide Girolami](https://sites.google.com/site/davegirolami/). 

- The code of the algorithm can be found in `QuantumRL.ipynb` file.
- The code in `quantum_state_tomography.ipynb` is used to reconstruct a quantum state via quantum tomography, given measures on a real device (See Abstract below for details). This state is then compared using fidelity score with the algorithm simulation in order to quanify the noise introduced by the real quantum device.

## Abstract
Quantum Computing promises to solve computational problems much faster than any classical computer, also unlocking solutions to challenges which can not be approached with classical processors in any useful amount of time. In this thesis we want to combine the power of reinforcement learning with quantum computing: the goal is to train an agent to design a quantum circuit which transforms an initial state vector associated to a quantum system into a target state of interest. We proceed by introducing the principles of Reinforcement Learning, Quantum Mechanics and Quantum Computation. Then, we provide a detailed description of the algorithm constructed and the results obtained. The designed quantum circuit is then implemented and run on a real quantum device from IBM Quantum Lab, to provide a comparison between classical simulation and quantum experiment

## Resources
You can consult the full manuscript at the [Thesis Portal](https://webthesis.biblio.polito.it/20525/) of Politecnico di Torino. The slides for the presentation of the thesis are available at [slides-presentation.pdf]()