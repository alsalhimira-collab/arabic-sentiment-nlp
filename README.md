## Overview
This project builds a sentiment analysis system for Arabic text to classify reviews into Positive, Neutral, and Negative sentiments.

## Dataset
- Arabic text dataset
- 1193 samples
- Balanced classes

## Methods
- TF-IDF + SVM
- FastText + BiLSTM
- AraBERT Transformer (fine-tuned)

## Results
| Model | Accuracy | Macro-F1 |
|-------|-----------|-----------|
| TF-IDF + SVM | 0.64 | 0.64 |
| FastText | 0.53 | 0.48 |
| AraBERT | 0.69 | 0.69 |

## Tech Stack
Python, Scikit-learn, TensorFlow/Keras, Transformers, NLTK

## Files
- NLP_22110377.ipynb → main notebook
- Report PDF → analysis and explanation

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook



