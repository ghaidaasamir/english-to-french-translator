# english-to-french-translator

## Overview
This project implements a sequence-to-sequence (Seq2Seq) neural machine translation model using TensorFlow and Keras. The model is trained to translate sentences from English (source language) to French (target language) using an encoder-decoder architecture with LSTM (Long Short-Term Memory) layers.

## Files
- **source data (small_vocab_en)**: Contains the English sentences for training.
- **target data (small_vocab_fr)**: Contains the French translations corresponding to the English sentences.

## Dependencies
To run this project, the following Python packages are required:
- TensorFlow
- NumPy

## Data Preparation
- **Loading Data**: Data is loaded from text files, where each line contains a sentence in the respective language (English or French).
- **Text Preprocessing**:
    - Sentences are converted to lowercase and tokenized using Keras' Tokenizer.
    - Sentences are then converted into integer sequences.
    - Sequences are padded to a fixed length to ensure uniformity across the dataset.

## Notes
- The model is designed for small-scale vocabulary translation tasks.
