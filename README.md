# energy-forecasting-lstm-gru-pytorch
Forecasting hourly energy consumption using LSTM and GRU deep learning models built in PyTorch on the PJM dataset.


⚡ Energy Consumption Prediction using LSTM & GRU (PyTorch)

This project implements and compares LSTM and GRU models using PyTorch to forecast hourly energy consumption. It addresses the challenges of temporal dependencies in energy usage using deep learning techniques, and evaluates each model’s performance using real-world data.

🎯 Objective

Accurately forecast energy usage based on historical consumption patterns to support better power grid management, demand planning, and energy trading. Traditional models fail to capture non-linearity and sequential patterns—this project uses LSTM and GRU to solve that.

📊 Dataset

Source: PJM Interconnection LLC Energy Dataset – Kaggle
https://www.kaggle.com/datasets/robikscube/hourly-
energy-consumption

Data: Hourly energy usage across U.S. regions.

Features: Timestamps, region-wise consumption, etc.

🛠️ Methodology

🔧 Data Preprocessing
Handled missing values and outliers

Normalized data for efficient model training

Created input-output sequences (lookback windows)

🧠 Model Implementation (PyTorch)

Designed LSTM and GRU networks

Defined architecture (layers, hidden units, sequence length)

Trained models on hourly data

📈 Evaluation

Metrics:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Visualizations:

Predicted vs Actual energy consumption plots

Loss trends over epochs

🧪 Results

Both models performed well in learning temporal energy patterns.

[Insert Best Model Here] achieved lower MSE/RMSE.

Visual predictions closely match actual energy usage.

💻 Tech Stack

Python

PyTorch

NumPy, Pandas

Matplotlib, Seaborn

Scikit-learn

💡 Conclusion

The use of LSTM and GRU significantly improves the accuracy of energy consumption forecasting. These models are adept at capturing time-based patterns, outperforming traditional techniques. Future improvements could involve:

Integrating weather and holiday data

Using hybrid architectures (e.g., LSTM-CNN, GRU-Attention)



