# Stock-Market-Forcasting using LSTM

This project leverages Long Short-Term Memory (LSTM) neural networks to predict stock prices, focusing on Apple’s (AAPL) stock data. It integrates advanced preprocessing and modeling techniques to achieve accurate forecasts for time-series data.

# Project Workflow:

	1.	Data Collection:
	•	Stock data retrieved using the Tiingo API, with a focus on daily closing prices.
	2.	Data Preprocessing:
	•	Normalization using MinMaxScaler to ensure LSTM sensitivity to data scale.
	•	Transformation of time-series data into supervised learning format for effective training.
	3.	Modeling:
	•	Built an LSTM-based Sequential model:
	•	50 LSTM units for time-series feature extraction.
	•	Dense output layer for predicting future prices.
	•	Trained with 100 epochs and a batch size of 64.
	4.	Evaluation:
	•	Performance validated using metrics like Mean Squared Error (MSE) and visualization of predictions.

# Key Features:

	•	Custom preprocessing pipeline for feature engineering.
	•	Implementation of an LSTM model optimized for stock price prediction.
	•	Training-validation split to ensure robust model evaluation.

# Future Scope:

	•	Experimenting with advanced architectures like stacked LSTM or BiLSTM.
	•	Integration of additional features like trading volume or external market indicators.
