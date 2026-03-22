# Sentiment Analysis using Deep Learning (LSTM)

A Deep Learning model that classifies movie reviews as positive or negative using LSTM Neural Network.

## About the Project
This project builds on traditional ML sentiment analysis by upgrading to a Deep Learning approach using LSTM. The model is trained on the Keras IMDb dataset containing 50,000 movie reviews.

## Dataset
- Name: IMDb Movie Review Dataset
- Source: Keras Built-in Dataset
- Size: 25,000 training + 25,000 testing reviews
- Top 10,000 most common words used

## Tech Stack
- Python
- TensorFlow
- Keras
- LSTM Neural Network
- NumPy
- Google Colab

## Model Architecture
- Embedding Layer: converts words to dense vectors
- LSTM Layer 1: 128 units
- LSTM Layer 2: 64 units
- Dropout Layer: 0.3
- Dense Output Layer: sigmoid activation

## Model Performance
- Training Accuracy: 94.75%
- Validation Accuracy: 86.80%

## Comparison with Traditional ML
| Model | Accuracy |
|-------|----------|
| Logistic Regression + TF-IDF | 84.00% |
| LSTM Neural Network | 86.80% |

Deep Learning outperforms traditional ML by 2.8%

## What I Learned
- Building LSTM Neural Networks using Keras
- Text tokenization and padding for deep learning
- Using EarlyStopping to prevent overfitting
- Comparing ML vs Deep Learning approaches
