# Model Card

## Model Description

**Input:** Takes input between 2 and 8 dimensions

**Output:** Return a value

**Model Architecture:** Gaussian Process Regressor with RBF kernel

## Performance

The model is evaluated against a black box functions, the inputs are compared between participant of the competition and a ranking is then created. For each function, this specific model ranked between 10th and 20th out of 40.

## Limitations

This model is not  optimized for each function

## Trade-offs

The model seems to be better suited for a low number of dimensions as input (2 and 3)