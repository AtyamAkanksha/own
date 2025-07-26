# own
This project uses scikit-learn’s MLPRegressor to predict continuous output from a single input feature. A small dataset is scaled using StandardScaler for better convergence. A neural network with one hidden layer learns the pattern and predicts values like the output for input 65.

Neural Network Regression using MLPRegressor (Scikit-learn):
This project demonstrates a simple Multi-Layer Perceptron (MLP) model for performing regression using scikit-learn's MLPRegressor. The model is trained on a small dataset of numerical input-output pairs (e.g., marks vs scores), with feature scaling applied to improve performance and convergence.

Problem Statement:
We aim to predict a continuous output (e.g., score or price) given a single input feature. For example, given input x = 65, the model predicts the corresponding y value based on patterns learned from the training data.

Model Details:
•	Model: MLPRegressor (Neural Network)
•	Hidden Layers: 1 layer with 2 neurons
•	Activation: ReLU (default)
•	Solver: Adam (default)
•	Iterations: 5000 (max_iter) to ensure convergence
•	Scaling: StandardScaler used for input and output normalization

Sample Data:
x = [50, 60, 70, 80]
y = [150, 180, 210, 250]


Key Steps:
1.	Reshape data into 2D arrays
2.	Apply standard scaling using StandardScaler
3.	Train MLPRegressor on scaled data
4.	Predict for a new input (e.g., 65)
5.	Inverse transform output to get real-world value

Dependencies:
•	numpy
•	scikit-learn
•	matplotlib (optional for visualization)
