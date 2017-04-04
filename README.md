# AdvancedMachineLearning
Code for class 02460 Advanced Machine Learning at Technical University of Denmark.
## Assignment: 
Modeling Micro-states using directional statistics for Brain activity EEG data.
## Goals: 
a) Develop mixture model based on the Watson Distribution.
b) Model dynamic connectivity and micro-states in neuroimaging.
c) Quantify the number of micro-states using prediction.
## Decisions:
a) A Hidden Markov model (HMM) based Expectation–maximization algorithm (EM) is used for classification.
b) The values for the Watson distribution of the HMM-EM are initialized using a Gaussian-EM.
c) A log(sum(exp)) and Kummers function for stability of transformation.
