# Discrete-Hopfield-Network
# Aim
Implement a program to store a pattern (1 1 1 -1) using a Discrete Hopfield Network and test its ability to recognize the pattern when given input with mistakes in the first and second positions.

Date of Performance
12/10/2023

# Overview
This project demonstrates how a Discrete Hopfield Network functions as an associative memory model. The network stores a given pattern using Hebbian learning and is tested with noisy inputs to check if it correctly recalls the original pattern.

Features
Pattern Storage: Stores the binary pattern (1 1 1 -1) in the Hopfield Network.
Hebbian Learning Rule: Computes the weight matrix to store the pattern.
Error Correction: Tests the network with noisy inputs where mistakes exist in the first and second positions.
Pattern Recognition: Recovers the original pattern even when minor errors are introduced.
📦 Dependencies
To run the program, install NumPy if not already installed:

pip install numpy
