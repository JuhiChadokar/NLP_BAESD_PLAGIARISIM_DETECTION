NLP Plagiarism Detection using Siamese LSTM
Overview

This project uses a Siamese LSTM neural network to detect plagiarism between two pieces of text. Given a source text and a candidate text, the model encodes both using shared embedding and LSTM layers, compares their representations, and predicts whether the candidate is plagiarized (semantically similar) or not.

Key points:

Dataset: MIT Plagiarism Detection dataset (source text, candidate text, label)
Preprocessing: text cleaning (lowercasing, punctuation removal) + tokenization/padding
Model: Siamese LSTM (shared weights) with a Dense classification head
Output: binary prediction — plagiarized vs. not plagiarized
Includes a predict_pair() function to test the model on custom text pairs