# Implementing-Iris-Classification-using-a-QUBO-model-with-D-Wave-s-Ocean-SDK
A project on optimal dataset clustering for machine learning training, formulated as a Quadratic Unconstrained Binary Optimization (QUBO) problem and solved using Quantum Annealing and Simulated Quantum Annealing on a D-Wave quantum computer using Ocean SDK. This was the final project of the course by Jean Senellart, Chief Product Officer of Quandela, in collaboration with Paris-Saclay University during my Erasmus Mundus Joint Master Program "Quandela" in Quantum Science and Technology.

Language: Python

◦ Defined a QUBO problem to minimize intra-cluster distances, with two penalties: one enforcing single-cluster membership per point and the other ensuring balanced cluster sizes.

◦ Solved the problem with and without the second penalty using both quantum and simulated annealing. Analysed the benefits of the second penalty.

◦ Compared the advantages of using a quantum computer versus a simulated one, based on current free access resources offered by D-Wave.
