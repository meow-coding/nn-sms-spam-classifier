# Neural Network SMS Spam Classifier

A neural network model that classifies SMS messages as **ham** (normal message) or **spam** (advertisement). Built using **TensorFlow**, trained on the UCI SMS Spam Collection dataset.

## Features

- Classifies messages with ~87% accuracy on the test set
- `predict_message(message)` function to classify new messages
- Visualizations:
  - Training vs validation accuracy
  - Confusion matrix
  - Distribution of predicted probabilities
- Dataset split into training (80%) and test (20%)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/<your-username>/nn-sms-spam-classifier.git
cd nn-sms-spam-classifier