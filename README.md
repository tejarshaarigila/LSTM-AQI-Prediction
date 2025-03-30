# Forecasting Air Quality in Kansas City using LSTM

## Overview

The "LSTM-Prediction" project utilizes Long Short-Term Memory (LSTM) networks to forecast time-series data. LSTM networks are a type of recurrent neural network (RNN) adept at capturing temporal dependencies, making them suitable for tasks like time-series forecasting.

## Repository Contents

- **LSTM_AQI.ipynb**: A Jupyter Notebook demonstrating the application of LSTM networks to predict Air Quality Index (AQI) values based on historical data.

## Requirements

To run the provided notebook and ensure compatibility, it's recommended to use the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `tensorflow`
- `keras`

These libraries can be installed using pip:

```bash
pip install numpy pandas matplotlib tensorflow keras
```

## Usage

1. **Data Preparation**: Ensure that your time-series dataset is in a CSV format with a datetime index and the target variable (e.g., AQI values).

2. **Notebook Execution**: Open `LSTM_AQI.ipynb` in a Jupyter environment.

3. **Model Training**: Follow the notebook's steps to preprocess the data, define the LSTM model architecture, and train the model on your dataset.

4. **Prediction**: Use the trained model to make forecasts and visualize the results as demonstrated in the notebook.

## License

This project is licensed under the MIT License.

## References

Environmental Protection Agency. (2024.). *Outdoor air quality data*. Retrieved from [https://www.epa.gov/outdoor-air-quality-data](https://www.epa.gov/outdoor-air-quality-data)
