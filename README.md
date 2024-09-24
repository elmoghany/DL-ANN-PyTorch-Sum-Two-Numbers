# Introduction
Machine Learning is not very good at Maths but if trained on all calculations with large datasets, it can predict the results very well.

# Illustration
1) Training: We train a linear ANN model on the dataset
2) Input features: 2 features
3) Output Target: 1 target "sum of two input features"

# Model & Architecture
1) ANN DL Model
2) input layer:   2  -> leaky_relu -> 20 
3) Hidden Layer1: 20 -> leaky_relu -> 10
4) Hidden Layer2: 10 -> leaky_relu -> 5
5) Output Layer:  2  -> 1
6) Normalize inputs using min-max
8) Use of MSELoss because we predict a continuous number

# Results
1) Accuracy: Got 100% accuracy for the prediction of the sum of the two numbers

# Conclusions:
1) After trying with simple 1 layer model and multiple layers model; There is no need for complexity of the model with more than 1 layer. Both got 100% accuracy.
2) Linear calculations <=use=> Linear Model with 1 layer
