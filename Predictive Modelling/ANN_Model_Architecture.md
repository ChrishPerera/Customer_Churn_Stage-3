
# Defined Architecture of ANN Model

The Artificial Neural Network model was developed to predict customer churn as a binary classification problem.

## Input Layer
The input layer contains one neuron for each feature in the preprocessed customer dataset.

## Hidden Layers
The model uses two hidden layers:

- Hidden Layer 1: 64 neurons with ReLU activation
- Hidden Layer 2: 32 neurons with ReLU activation

ReLU activation was selected because it helps the model learn non-linear relationships in the data.

## Output Layer
The output layer contains one neuron for binary classification.

The model predicts whether a customer is likely to churn or remain with the company.

## Optimisation Algorithm
The Adam optimiser was used to improve model convergence and training performance.

## Evaluation Metrics
The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
