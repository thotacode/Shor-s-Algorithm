Shor's Algorithm Implementation

Overview - 
This Jupyter Notebook implements Shor's Algorithm for factoring large integers using quantum computing principles. It doesn't leverage the Qiskit library to create and simulate quantum circuits,
we use vanilla Python to give a classical representation, and to impress upon users the increased speed and efficiency quantum computing can offer, by using the code of quantum unitary matrices.

Installation and Setup - 
Clone the Repository- 

git clone https://github.com/thotacode/Shor-s-Algorithm.git
cd Shor-s-Algorithm

Install Dependencies -
Ensure you have Python and pip installed, then run:
pip install -r requirements.txt

Usage - 
Open the Jupyter Notebook:
jupyter notebook SHORFINAL.ipynb
Follow the cells sequentially to understand and execute Shor's Algorithm.

Code Explanation - 

Imports and Dependencies - 

import numpy as np
import matplotlib
This section imports essential libraries and modules.

Class and Function Definitions - 

QFT (Quantum Fourier Transform): A helper function to perform the QFT.
Modular Exponentiation: Function to compute modular exponentiation.
Shor's Algorithm Class: Contains methods to perform the steps of Shor's Algorithm.

Main Algorithm Steps - 
Input Handling: Input the number to be factored.
Quantum Phase Estimation: Quantum circuit implementation for phase estimation.
Finding the Period: Classical post-processing to find the period from quantum measurement.
Factorization: Using the period to find the non-trivial factors of the number.

Example Execution
An example is provided to factorize a number:

input = 15.

The factors are [3,5]
The notebook includes visualization of the quantum circuit and measurement results:

plot_histogram(result.get_counts())
This generates a histogram to visualize the probability distribution of measurement outcomes.

Conclusion - 

This implementation demonstrates the practical application of Shor's Algorithm using quantum computing, highlighting the potential for efficient factorization of large numbers.

References -
Shor, P.W. (1994). Algorithms for quantum computation: Discrete logarithms and factoring. Proceedings 35th Annual Symposium on Foundations of Computer Science.

The code has been written by -
1)Pranav Reddy Thota
2)Rithul C
3)Anshul Rath
4)Aaditya Rajput

For more details, refer to the GitHub repository.
