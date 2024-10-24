# Next Word Prediction with LSTM on Data Sonnet

Overview

This project implements a Next Word Prediction model that predicts the next word in a sentence using the "Sonnet" dataset. By leveraging Natural Language Processing (NLP) techniques, this model enhances text input efficiency in applications such as chatbots, writing assistants, and auto-completion features.

Key Steps
    
    Dataset Preparation: 
    Loaded and tokenized Shakespeare's sonnets to convert text into sequences of word tokens.
    
    Text Preprocessing: 
    Created sequences of tokens and padded them for uniform length, generating predictors (input sequences) and labels (target words).
    
    Model Building: 
    Designed an LSTM-based model with an embedding layer for word representation and dropout layers for regularization.
    
    Training: 
    Trained the model using the tokenized sequences to predict the next word.
    
    Text Generation: 
    Developed a function to generate Shakespeare-like text given a seed phrase.

Technologies Used
    
    Python
    TensorFlow/Keras for deep learning
    LSTM neural networks
    Natural Language Processing (NLP)
        
