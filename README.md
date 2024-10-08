# Beginning:
This repository contains a simple neural network implementation for predicting the next number in a sequence using PyTorch. The model performs horribly with the current parameters. Try tuning the amount of neurons, dropout rate and epoch for better performance.

# Code Overview
Model: SimpleNN with two hidden layers and dropout for regularization.
Dataset: Example dataset of sequential even numbers.
Objective: Predict the next number in a sequence.


# Usage
## Install Dependencies

```bash
pip install torch torchsummary
```

## Notes
Dropout: Used for regularization with a dropout rate of 25%.
Training: Runs for 10,000 epochs with SGD optimizer.