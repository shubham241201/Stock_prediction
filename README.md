## Stock Prediction for BAJAJ

Project Report 
Topic- Stock Prediction Model

INTRODUCTION
Predicting Predicting stock prices is a challenging task as it depends on various factors including but not limited to geopolitics, global economy, company’s financial reports and performance, etc. In this project, I created a model to predict the next day’s closing price based on last n-days of data. We use LSTM and RNN in this Project.

PROBLEM STATEMENT
Predicting Predicting stock prices is a challenging task as it depends on various factors including but not limited to geopolitics, global economy, company’s financial reports and performance, etc. There are two main approaches to predicting the stock price: Technical analysis method uses metrics like closing and opening price, the volume traded, adjacent close values etc. of the stock for prediction, whereas qualitative analysis looks at external factors like company profile, market situation, political and economic factors, textual information in news, social media and even blogs by the economic analyst.
Your task is to create a model to predict the next day’s closing price based on last n-days of data.

Once you predict the next day’s closing value, do the same for 10 days data (How close are you for 10 predictions)?Using this model, if you invest 10000 for each of the 10 days wherever it shows profit. What is your return value?


THE DATASET
  BAJAJFINSV.NS.csv is the Dataset I used with the following attributes:
Open: Price at which stock started trading when market opened on a particular date.
Close: Price at which stock started trading when market closed on a particular date. Last buy/sell order executed between two traders.
High: Highest price at which the stock traded during the period.
Low: Lowest price at which the stock traded during the period.
Volume: Total amount of trading activity during a period of time.
Adj Close: Calculation adjustment to the stock’s closing price. It is more complex and accurate than the closing price. 

Machine learning model
Concepts of Deep Learning have been using in this project.
Deep Learning:  The deep learning study is a sub-field of machine learning algorithms inspired by the concerns and the structure and function of the brain, this is call artificial neural network. Most of the learning method uses neural network architecture, which is why you want to study deep learning model is commonly referred to as a deep neural network.
Deep learning architectures:
1.Recurrent neural network (RNN): It is a class of artificial neural network where connections between units form a directed graph along a sequence. 
2.Long short-term memory (LSTM): LSTM is a RNNS to capture long-term dependency on time series forecasting
We use both of these in this model.
The motivation behind the use of these two methods LSTM and RNN to determine if there are any long-term dependence on existing in a given data or not. This can be determined from the performance model. The LSTM and RNN architecture to identify long-term dependencies, and they are used to predict the future.

CONCLUSION
I believe the interface provides a way to predict closing values of stocks for 10 days.

LINK FOR THE PROJECT:
https://colab.research.google.com/drive/1OhW8LJXtqeNsGcqg6zacUdA5tnUhOxej?usp=sharing
Submitted by- Shubham Chaudhary