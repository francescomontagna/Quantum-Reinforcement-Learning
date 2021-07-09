# Quantum-Reinforcement-Learning
Implementation of proof of concept quantum enhancing reinforcement learning algorithm, able to find the sequence of quantum gates needed to approximate a given function: the goal is to train an agent to design a quantum circuit transforming any given initial quantum state into another given target state. This should be done minimizing the number of gates used.

The algorithm is still under development for my Master Thesis Project at Politecncio di Torino. I am planning to complete it in the next weeks / few months, I'll keep this README updated.  

UPDATE: The algorithm is working (quite well). Ideally, I willd develop a script in next weeks in such a way that introducing an initial and a target state, it provides the designed circuit in output, which can be run on any real device. After the thesis discussion, I will also publish the master thesis itself, describing the algorithm in detail.

TODO:
- [X] Cleanup of comments
- [ ] Plots (need to make heat map understandable)
- [X] Compare theoretical results with experimental from [IBM Quantum Composer](https://quantum-computing.ibm.com/composer/files/new)
- [ ] Create runnable script
