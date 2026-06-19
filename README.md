# "Linear Regression Model with PyTorch

# Description:
A simple linear regression model trained using PyTorch's Adam optimizer.
The model is trained on normalized data (Z-score normalization) to ensure 
stable convergence. Key features include gradient clipping and a conservative 
learning rate to prevent gradient explosion.

# Technical Details:
- Framework: PyTorch
- Model: Linear Regression (y = w*x + b)
- Optimizer: Adam (learning_rate=0.001)
- Loss Function: Mean Squared Error (MSE)
- Training: 500 epochs
- Data Preprocessing: Z-score normalization
- Validation: R² score, MAE, RMSE
"
