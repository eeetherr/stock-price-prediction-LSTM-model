# stock-price-prediction-LSTM-model

## Overview
This project implements a Long Short-Term Memory (LSTM) neural network using Keras for stock price prediction. The model is trained on historical stock data, and its predictions are visualized for assessment.

## Table of Contents
- [Project Highlights](#project-highlights)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Collaboration](#collaboration)

## Project Highlights
- Implemented an LSTM-based stock price prediction model in Keras.
- Utilized Min-Max scaling for effective data preprocessing and normalization.
- Designed a robust LSTM architecture with dropout regularization for optimal generalization.
- Monitored and visualized training progress using matplotlib for clear insights into model performance.
- Applied the trained model to predict Google stock prices on unseen test data, ensuring practical utility.
- Shared the project via Google Colab, highlighting collaborative coding practices and project accessibility.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stock-price-prediction.git

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Usage
-Open the project in a Jupyter notebook or a code editor.
-Run the notebook cells to train the model and make predictions.
-Explore the visualizations and assess the model's performance.

## Project Structure
-data/: Directory containing the historical stock data CSV files.
-notebooks/: Jupyter notebooks for data preprocessing, model training, and prediction.
-results/: Visualizations and results generated by the model.
-Google_train_data.csv: CSV file containing historical training data.
-Google_test_data.csv: CSV file containing unseen test data.
-README.md: Project overview and instructions.

## Results

Figure 1: Training model loss over epochs.

![image](https://github.com/sakshamdev123/stock-price-prediction-LSTM-model/assets/105414841/ec86499b-18fb-4a42-bc91-84ea896e685c)

Figure 2: Actual vs Predicted Stock Prices.

![image](https://github.com/sakshamdev123/stock-price-prediction-LSTM-model/assets/105414841/da84102f-c726-4a4e-a4a1-a48a55d380be)

## Collaboration
Collaborate on the project using Google Colab by opening the provided notebook.
Feel free to open issues or pull requests for improvements.
