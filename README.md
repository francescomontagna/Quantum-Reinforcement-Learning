# Quantum-Reinforcement-Learning
Implementation of proof of concept quantum enhanced reinforced learning algorithm, able to find the sequence of quantum gates needed to approximate a given function.

The algorithm is still under development for my Master Thesis Project at Politecncio di Torino. I am planning to complete it in the next weeks / few months, I'll keep this README updated.  

UPDATE: The RL algorithm works correctly, I implemeted systematic experiments with initial state = |00> and randomly generated target state. All tests on a pair (initial_state, terminal_state) are repeated using [Google Cirq](https://quantumai.google/cirq) framework to check for correctness.

TODO:
- [ ] Cleanup of comments
- [ ] Plots
- [X] Compare theoretical results with experimental from [IBM Quantum Composer](https://quantum-computing.ibm.com/composer/files/new)
- [ ] Create runnable script
- [ ] Policy learning: define early stop condition
