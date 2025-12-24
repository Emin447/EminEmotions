# EmotionsText_AI_20240109

Text-based Emotions AI model using BiLSTM.

## Description

This project trains a neural network to classify emotions from text data. It uses a CSV dataset with columns:

- `text` : input text data
- `label`: emotion label (categorical)

The model workflow:

1. Load CSV dataset
2. Train/test split (80/20)
3. Tokenize and pad sequences
4. BiLSTM model:
   - Embedding layer
   - Bidirectional LSTM
   - Dense layers
5. Train model with validation
6. Plot accuracy & loss
7. Evaluate test accuracy
8. Save model as `EmotionsText_AI_20240109.h5`

## Requirements

See `requirements.txt` for all dependencies with versions.

## Usage

1. Upload `emotions.csv` to Colab or project folder.
2. Run the Colab notebook to train and evaluate the model.
3. Model will be saved as `EmotionsText_AI_20240109.h5`.
