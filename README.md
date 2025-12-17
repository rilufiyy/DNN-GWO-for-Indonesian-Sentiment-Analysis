# DNN-GWO Sentiment Analysis (IndoNLU SMSA)

This project implements a Deep Neural Network (DNN) for Indonesian sentiment
analysis using the IndoNLU SMSA dataset. Hyperparameter tuning is performed
using the Grey Wolf Optimizer (GWO) to improve classification performance.

## Dataset
- **IndoNLU – SMSA**
- Task: Sentiment Analysis
- Labels: Positive, Neutral, Negative
- Language: Indonesian

## Method
1. Text preprocessing
2. Feature representation
3. DNN model construction
4. Hyperparameter optimization using Grey Wolf Optimizer (GWO)
5. Model evaluation

## Optimized Hyperparameters
- Number of hidden layers
- Number of neurons
- Learning rate
- Batch size
- Dropout rate

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Technologies
- Python
- TensorFlow / PyTorch
- Scikit-learn
- NumPy, Pandas

## How to Run
```bash
pip install -r requirements.txt
python src/train.py
