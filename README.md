# Stock-Price-Prediction-using-LSTM
Stock prices change every day based on patterns over time. Normal machine learning models struggle with this, but a special deep learning model called an LSTM handles it perfectly.  In this project, I use a dataset of stock prices for TCS.

# Stock Price Prediction using LSTM

Hello! This is my deep learning project for time-series forecasting. The main goal of this notebook is to look at past stock prices and predict what the future price will be.

## What I do in this project
Stock prices change every day based on patterns over time. Normal machine learning models struggle with this, but a special deep learning model called an LSTM handles it perfectly.

In this project, I use a dataset of stock prices for TCS. 

Here are the steps I follow:
1. **Data Preprocessing:** I clean the data and use a scaler (like MinMaxScaler) to make all the price numbers very small (between 0 and 1). Neural networks learn much better this way.
2. **Building the Model:** I build an LSTM (Long Short-Term Memory) neural network. LSTMs are great for this job because they have a "memory" that remembers past stock price trends.
3. **Training and Testing:** I train the model on the older stock prices. Then, I ask it to predict the newer stock prices to see how smart it got.

At the end of the notebook, I draw a line graph. This graph compares the real stock prices with my model's predicted stock prices so you can visually see the accuracy!

## Libraries I use
* **TensorFlow and Keras:** For building and training the LSTM neural network
* **numpy and pandas:** For organizing the time-series data
* **scikit-learn:** For scaling the data numbers
* **matplotlib:** For drawing the final line graph

## How to use
Just download the `stock_price_prediction_lstm.ipynb` file. Open it in Jupyter Notebook or JupyterLab. Run the cells to see how I prepare the data, train the LSTM model, and view the final prediction graph.
