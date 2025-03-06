### Time Series Forecasting of Microsoft Stock Price Using Simple RNN and Bidirectional LSTM

### Overview:
This project aims to predict the Adjusted Closing Price of Microsoft stock using time series forecasting techniques. Two deep learning models—Simple RNN and Bidirectional LSTM—are implemented and evaluated. Before model training, the dataset is normalized, and a Time Series Generator is used to prepare the sequential data. The models are compared using Mean Squared Error (MSE) and Mean Absolute Error (MAE), and the results indicate that Simple RNN outperforms Bidirectional LSTM with lower error values.

### Steps Involved:
1. Data Collection & Preprocessing:
a. Loading the Microsoft stock price dataset.
b. Extracting the Adjusted Closing Price as the target variable.
c. Normalized the data for better model performance.

2. Data Preparation Using Time Series Generator:
a. Converted the time series data into supervised learning format.
b. Splitted the data into training and testing sets.

3. Model Training:
a. Training a Simple RNN model.
b. Training a Bidirectional LSTM model.

4. Model Evaluation:
a. Compared both models using MSE and MAE.
b. Identified the best-performing model.

### Results:
a. Simple RNN achieved lower MSE and MAE compared to Bidirectional LSTM, making it the better-performing model.
b. The findings suggest that Simple RNN is more effective than Bidirectional LSTM in forecasting Microsoft’s stock prices.













