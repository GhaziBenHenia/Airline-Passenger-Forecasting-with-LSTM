# Airline Passenger Forecasting with LSTM

## Project Overview
This project aims to forecast airline passenger traffic using historical data. By employing a Long Short-Term Memory (LSTM) neural network, we model the time series data to predict future passenger counts. The dataset contains monthly passenger numbers spanning from 1949 to 1960.

## Methodology
The core of this project involves preprocessing the airline passenger dataset and then applying an LSTM model for regression to predict future values. The LSTM model is chosen for its ability to capture temporal dependencies and patterns in time series data, making it particularly suited for forecasting tasks like this one.

## Dependencies
To run this project, you will need the following Python libraries:
- Numpy
- Pandas
- Matplotlib
- Keras (with TensorFlow as backend)
- Scikit-learn

These dependencies are crucial for data manipulation, visualization, model building, and evaluation.

## Getting Started
1. Ensure you have Python installed on your machine.
2. Install the required libraries using pip:
   ```
   pip install numpy pandas matplotlib keras tensorflow scikit-learn
   ```
3. Clone this repository or download the project files.
4. Run the `Airline_Passenger_Forecasting_with_LSTM.ipynb` notebook in a Jupyter environment or similar tool that supports IPython notebooks.

## Dataset
The dataset `airline-passengers.csv` is included in the project files. It consists of two columns: `Month` (ranging from January 1949 to December 1960) and `Passengers` (the number of passengers in thousands).

## Model Training and Evaluation
The notebook guides you through loading the dataset, preprocessing the data, defining the LSTM model, training the model, and finally evaluating its performance using metrics like RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and MAPE (Mean Absolute Percentage Error).
