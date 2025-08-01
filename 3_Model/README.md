# Model Definition and Evaluation

In this stage, we define, implement, and evaluate a neural network model to improve upon the baseline predictive performance. The goal is to minimize the Mean Absolute Percentage Error (MAPE) on both the training and validation datasets. 

## Contents

- **Model Selection**: Different architectures were tried. The most successful one is documented in chapter 6.

- **Feature Engineering**: Most of it was done and documented in Data Preparation. Additional efforts can be found in chapter 3.

- **Hyperparameter Tuning**: These decisions are done in chapter 6 before the start of the training.

- **Implementation**: The printout of the progress takes the rest of chapter 6.

- **Evaluation Metrics**: A diagram shows the decrease of the loss function, and MAPE is calculated in chapter 7.

## Systematic approach

1. Initial Training: Begin by using the full set of features from the baseline model to train a neural network with a basic architecture. 

2. Architecture Tuning: Experiment with different neural network configurations, including the number of hidden layers, neurons per layer, dropout layers, dropout rates, learning rate, epoch and batch size. The ReLU activation function is used consistently across all hidden layers. The objective is to identify an architecture for which further tuning does not lead to a meaningful reduction in MAPE on either the training or validation set.

3. Feature Selection: With the optimal architecture from Step 2, explore different combinations of input features. The goal is to identify a final model configuration—both in terms of architecture and input variables—that achieves the best generalization performance, as measured by stable or minimal MAPE across both datasets.

4. Additional features: To capture seasonal or periodic patterns in this timeseries data, additional cyclical features (e.g., sine and cosine transformations of the month and day of the week) are created and tested.

## Conclusion

Many things were tried out to find improvement. The version of the file that in the end proved to produce the best performing model is documented with this notebook. The success of this model can be seen in the fact that the MAPE on the Validation Data (17.93%) is only a little higher than the MAPE on the Training Data (16.21%).
