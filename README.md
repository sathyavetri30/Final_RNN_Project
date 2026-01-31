This project implements time series forecasting on the Household Power Consumption dataset using an optimized Transformer-based deep learning model, with an LSTM baseline for comparison. The pipeline includes data cleaning, feature scaling, sequence generation, rolling-window cross-validation, and model evaluation.

🚀 Features

Robust data preprocessing & missing value handling

Transformer encoder with multi-head self-attention

Rolling window cross-validation for reliable evaluation

Performance metrics: RMSE, sMAPE, MASE

Optimized training to avoid memory issues

Automatic saving of the best Transformer model

🛠️ Technologies Used

Python

Pandas, NumPy

Scikit-learn

TensorFlow / Keras

📁 Dataset

household_power_consumption.csv
Required columns:

global_active_power

global_reactive_power

voltage

global_intensity

sub_metering_1

sub_metering_2

sub_metering_3

time

▶️ How to Run
python final_project_rnn.py

📈 Output

Cross-validation performance for Transformer & LSTM

Saved model: best_transformer_model.h5

🎯 Objective

To demonstrate that Transformer models outperform traditional RNN-based models in multivariate time series forecasting tasks.# Final_RNN_Project
