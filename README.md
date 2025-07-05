# LSTM-Stock-Price-Prediction-with-Scoring-Based-Fine-Tuning
The Core Idea:

Inspired by RLHF, we try to apply same concept in time series forecasting

Our approach revolves around three key components:

1. An LSTM model for initial stock price predictions 2. A scoring model to evaluate the quality of these predictions 3. A fine-tuning process that uses the scoring model's output to refine the LSTM's performance

By integrating these components, we aim to create a more adaptive and accurate prediction system that can better capture the nuances of stock price movements.

Scoring Model: The scoring model is a separate neural network designed to evaluate the quality of the LSTM's predictions. It takes as input both the original price sequence and the LSTM's prediction, outputting a score that represents the predicted accuracy of the LSTM's forecast.
