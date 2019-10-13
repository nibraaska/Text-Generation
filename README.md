# TextGeneration

A cool application of Artificial Intelligence is text generation. This repository contains a neural network using
Long Short-Term Memory (LSTM) for text generation. 

# Files
- LSTMDeep.ipynb: This is a jupyter notebook file that contains the model for text generation. 
The model is built using the Cuda implementation of LSTM known as CuDNNLSTM to speed up learning on the GPU. 
The flow of the model is the following:
  1. Read in a text file of data
  2. Break the data into tokens
  3. Create training data by creating X and Y based on the tokens
  4. Train the network 
  5. Generate new text with the learned network 
  
- dylanThomas.txt: Training and testing data from the works of Dylan Thomas 
- emilyDickinson.txt: Training and testing data from the works of Emily Dickinson
- dylanThomasAdam.h5: Saved model of the neural network with the Adam optimizer
- emilyDickinsonRMSprop.h5: Saved model of the neural network with the RMSprop optimizer
