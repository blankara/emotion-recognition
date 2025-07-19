# Emotion Recognition from Text using Transformers

This project uses a pre-trained transformer model (`j-hartmann/emotion-english-distilroberta-base`) to classify emotions in English text. It predicts emotions like joy, sadness, anger, fear, love, surprise, and neutral.

## How it works
- Model: DistilRoBERTa (fine-tuned for emotion detection)
- Dataset: GoEmotions / HuggingFace
- Language: Python (Google Colab, Hugging Face Transformers)

## Demo
You can input your own sentence and see the predicted emotion.

## Example
Input: `I'm so proud of you!`  
Output: `joy`

## Try it
Open the Jupyter notebook in Google Colab and run all cells.

## Requirements
- Python 3.8+
- transformers
- torch

## Author
This project was built by Blanka Rajchman as a portfolio piece for university applications.
