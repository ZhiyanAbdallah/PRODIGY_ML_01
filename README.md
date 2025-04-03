# House Price Prediction Using Neural Networks

# Problem Statement
Real estate professionals often struggle with accurately predicting house prices due to multiple influencing factors such as location, size, and amenities. Incorrect pricing can lead to prolonged sales periods or undervaluation. This project leverages machine learning to provide a data-driven approach to estimating house prices.

# Solution
This project implements a neural network using PyTorch to predict house prices based on various property features such as living area, number of bedrooms, garage size, and more. The model is trained on historical housing data and can be used to estimate prices for new properties.

# Technologies Used
- Python: Programming language
- PyTorch: Deep learning framework for model implementation
- Pandas: Data handling and preprocessing
- Matplotlib: Visualization of training loss
- Scikit-learn: Data scaling and preprocessing
- Google Colab: Cloud-based development environment

# Implementation Steps
1. Data Loading: Import training and test datasets directly from Google Drive.
2. Data Preprocessing:
   - Handle missing values by filling numeric columns with mean values.
   - Select key features relevant to house pricing.
   - Standardize data using `StandardScaler`.
3. Model Building:
   - Define a neural network with three layers using PyTorch.
   - Use ReLU activation functions in hidden layers.
   - Output a single predicted price.
4. Model Training:
   - Optimize using Adam optimizer and MSE loss function.
   - Train for 100 epochs, tracking loss over time.
5. User Input and Prediction:
   - Accept property details from users.
   - Apply the trained model to predict house prices based on input features.
   - Standardize user input before prediction.

# Business Impact
- Improved Pricing Accuracy: Provides data-driven pricing estimates to real estate professionals.
- Time Efficiency: Reduces manual effort in price evaluation.
- Market Insights: Helps sellers and buyers make informed decisions based on predictive analysis.
- Competitive Advantage**: Enables real estate agencies to leverage AI for more precise and strategic pricing.

# How to Use
1. Run the script in Google Colab.
2. Ensure the dataset paths are correctly set.
3. Train the model.
4. Input property details when prompted.
5. Get an estimated house price.

This model provides a practical tool for real estate professionals to enhance their pricing strategies using machine learning.

