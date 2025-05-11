# Weather Forecasting using LSTM (Long Short-Term Memory Networks)

This project uses a deep learning model — **LSTM (Long Short-Term Memory)** — to forecast temperature trends based on historical weather data. LSTM is well-suited for time-series prediction tasks.

## 📈 Key Features
- Data preprocessing and normalization
- Sequence generation for time-series prediction
- LSTM model built with Keras/TensorFlow
- Forecast visualization and evaluation

## 🧰 Packages Used
- Python 3
- `pandas`, `numpy` for data processing
- `matplotlib`, `seaborn` for visualization
- `TensorFlow` and `Keras` for deep learning


## 🧠 Model Architecture
- Input: Past N days of temperature data
- Layers: LSTM → Dense
- Output: Temperature prediction for next time step
- Optimizer: Adam | Loss: Mean Squared Error

## 📊 Example Visualization

```
Predicted vs Actual Temperature
+------------+------------+
|    Date    |  Temp (°C) |
+------------+------------+
| 2025-01-01 |    29.4    |
| 2025-01-02 |    28.8    |
+------------+------------+
```

## ▶️ How to Use

1. Open `11. lstm_weather.ipynb` in Jupyter Notebook or Colab
2. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn tensorflow
```
3. Run each cell in sequence to preprocess data, train the LSTM model, and generate forecasts.

## 💡 Tips
- Adjust window size (sequence length) to tune performance
- Normalize your data before training for better results
- Save model using `.h5` format for reuse

## 📄 License
MIT License © 2025 Md. Akiful Hoque Akif

## 🙋‍♂️ Author
Md. Akiful Hoque Akif  
[GitHub Profile](https://github.com/mdakif5717)
