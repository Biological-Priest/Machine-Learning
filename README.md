# Machine Learning

Different types of autoencoder scripts

- Simple autoeencoder

- Variational autoencoder

# Preprocessing 

There are different things to think about before pushing data into a machine. Below are a few things to consider in your pre-processing procedure. 

# 1. Encoding
This process is to take something that machine learning algorthims can't understand and convert it to something the machines do understand, such as word strings to number representation.Machines one of the most popular methods for preprossing a string, whether it be a words or sentences of classifying objects is using "One-hot Encoding". For example, the binary representation of a protein sequence. This method allows the mapping of DNA and/or protein sequences as numerical representation allows a neural networks / deep learning algorithms to take inputs.

A protein sequence of length L can be encoded as an L x n matrix, where n is the number of amino acids. Each row in the matrix consists of (n – 1) 0 s and a single 1, with the position of the 1 indicating the amino acid residue at that position in the protein.

# 2. Padding
Machines need to have everything the same dimensions and length. There are different type of padding processes, however, the most typical process is post-padding. This is forcing all data containing different dimensions and adding zeros to the trailing end of a sequence. 






