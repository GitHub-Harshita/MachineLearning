# 📈 Stock Price Prediction using LSTM, DNN, and Hybrid LSTM-DNN

## 🚀 Project Overview

This project focuses on predicting stock prices of the **Top 10 companies from the S&P 500 dataset** using Deep Learning techniques. The main objective is to compare the performance of three different models:

- LSTM (Long Short-Term Memory)
- DNN (Deep Neural Network)
- Hybrid Model (LSTM + DNN)

The project helps identify which model provides the most accurate stock price predictions and visualizes the comparative performance of all three models in a single graph.

---

## 🎯 Objective

The goal of this project is to:

- Predict future stock prices using historical stock market data
- Compare the performance of LSTM, DNN, and Hybrid LSTM-DNN models
- Determine which model performs best based on evaluation metrics
- Visualize model performance for better analysis and understanding

---

## 📊 Dataset

- **Dataset Used:** S&P 500 Dataset
- **Focus:** Top 10 companies
- Historical stock price data including:
  - Open
  - High
  - Low
  - Close
  - Volume
  - Adjusted Close

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras
- Jupyter Notebook

---

## 🧠 Models Implemented

### 1. LSTM Model
Used for capturing sequential dependencies and time-series patterns in stock market data.

### 2. DNN Model
Used for learning complex relationships from processed stock features.

### 3. Hybrid LSTM + DNN Model
A combination of LSTM and DNN to improve prediction performance by leveraging both sequential learning and deep feature extraction.

---

## 📈 Performance Comparison

All three models were trained and evaluated using the same dataset. Their prediction performance was compared using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Accuracy Visualization Graph

A single comparative graph was created to visually analyze which model performed best.

---

## 📷 Output Visualization

The project includes:

- Actual vs Predicted Stock Prices Graph
- Performance Comparison of LSTM vs DNN vs Hybrid Model
- Final model accuracy visualization in one graph

---

## 📂 Project Structure

```bash
Stock-Price-Prediction/
│
├── Final report (1).pdf
├── README.md
├── basics.pdf
├── s&p500filtered.csv
├── s&p500predictions.ipynb
