Predictive Maintenance: Remaining Useful Life (RUL) Estimation
This project implements a Remaining Useful Life (RUL) prediction system for turbofan engines using the CMAPSS dataset (FD001 subset) and Linear Regression. It includes data preprocessing, feature selection, training, evaluation, and visualization — along with engine health classification based on predicted RUL.

📁 Dataset
  \tSource: NASA's CMAPSS dataset

Files used:

  train_FD001.txt
  
  test_FD001.txt
  
  RUL_FD001.txt

✅ Features
  Linear regression model to predict RUL
  
  Data normalization with MinMaxScaler
  
  Sensor selection based on prior research

Health status classification:

  RUL > 80 → Healthy
  
  30 < RUL ≤ 80 → Needs Maintenance
  
  10 < RUL ≤ 30 → Immediate Maintenance Required
  
  RUL ≤ 10 → Unsafe to Use

Visualization:

  True vs. Predicted RUL (line plot)
  
  Prediction accuracy (scatter plot)

📊 Evaluation Metrics
  Mean Absolute Error (MAE)
  
  Root Mean Squared Error (RMSE)

📦 Dependencies
  pandas
  
  numpy
  
  matplotlib
  
  scikit-learn
