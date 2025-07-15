# 🌦️ Weather Forecasting using GRU

A deep learning model that predicts future temperature values using GRU (Gated Recurrent Unit) neural networks trained on historical weather data.

---

## 🧠 Objective

To forecast future weather trends (e.g., temperature) based on historical data using a GRU-based time series model.

---

## 📊 Dataset

- Historical weather data (e.g., temperature, humidity, wind)
- CSV format with time-indexed observations
- Sample columns: `Date`, `Temperature`, `Humidity`, `Wind Speed`

---

## 🧰 Tools & Libraries

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## 🏗️ Model Architecture

- GRU layers (1 or 2 stacked)
- Dropout for regularization
- Dense layer for output
- Loss: Mean Squared Error (MSE)
- Optimizer: Adam

---

## 📈 Results

- Training and validation loss plotted
- Predictive performance shown on test set
- Visualization of predicted vs actual temperature

![Model Output](model_plot.png)

---

## 📁 Files

- `weather_gru.ipynb`: Full model code with training and evaluation
- `weather_data.csv`: Sample dataset
- `model_plot.png`: Graph of predicted vs actual values

---

## 🔍 How to Use

1. Open the notebook `weather_gru.ipynb`
2. Run all cells to train and evaluate the model
3. Modify hyperparameters to experiment

---

## ✨ Author

Rowan Ibrahiem  
[LinkedIn](https://www.linkedin.com/in/rowan-ibrahiem-ba7571277) | [Email](mailto:rowanibrahiem@gmail.com)

---

## 📌 Note

This project is for educational and portfolio purposes only. The dataset is either simulated or publicly available.
