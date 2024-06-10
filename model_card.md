# Model Card

## Model Description

**Input:** Historical revenue data in float

**Output:** A single float number, the prediction of the revenue of the next month

**Model Architecture:** Neural network with 1 input layer, 1 hidden dense layer that is tuned within the range of 8 to 64 units (in steps of 8), and 1 output layer dense layer.

## Performance

The metrics used was MAE, the model evaluated well with a MAE of 109.8203, which is great considering the revenue figures are all in the tens of thousands.

## Limitations

This model was trained on just one year of data and for one client only, it would not be able to be used to make revenue predictions for another client.

## Trade-offs

The model was trained for 100 epochs, which might be a bit too much. This could also be included in the hyperparameter optimisation as well, but considering the time required, the idea of abandoned.
