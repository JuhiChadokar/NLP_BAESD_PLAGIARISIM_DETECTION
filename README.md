NLP Plagiarism Detection using Siamese LSTM
Overview

This project uses a Siamese LSTM neural network to detect plagiarism between two pieces of text. Given a source text and a candidate text, the model encodes both using shared embedding and LSTM layers, compares their representations, and predicts whether the candidate is plagiarized (semantically similar) or not.

Key points:

Dataset: MIT Plagiarism Detection Dataset — source text, candidate text, and label

Preprocessing: Text cleaning, lowercasing, punctuation removal, tokenization, and padding

Model: Siamese LSTM with shared weights and a Dense classification head
Output: Binary prediction — Plagiarized / Not Plagiarized

Includes a predict_pair() function to test the model on custom text pairs make this in bullet