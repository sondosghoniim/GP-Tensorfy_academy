# GP-Tensorfy_academy
# **Project Overview**
This project aims to perform sentiment analysis by combining insights from both textual reviews and related images. The goal is to build two deep learning models—one for analyzing sentiments from text (RNN-based) and another for analyzing sentiments from images (CNN-based). The project highlights the importance of multimodal learning in understanding complex sentiment cues.

#**Steps Followed**
1.Text Data Preprocessing
    Cleaning (removing HTML tags, punctuation, etc.)
    Tokenization
    Stopword removal
    Lemmatization
    Sequence padding and tokenization using Tokenizer
    
2.Image Data Preprocessing
    Resizing images
    Converting to array format
    Normalizing pixel values
    Augmentation using ImageDataGenerator

3.Model Building
    CNN Model for image sentiment classification
    RNN Model (LSTM/GRU) for text sentiment classification

4.Model Training
    Trained each model using the preprocessed datasets
    Used appropriate loss functions and optimizers

5.Model Evaluation
    Accuracy, Confusion Matrix, and Classification Report for both models

6.Model Saving
    Saved trained models for future use

#**Tools and Libraries Used**
Python
TensorFlow / Keras
NLTK
Scikit-learn
Pandas
NumPy
Matplotlib
