# BTC-to-USD-Prediction
## 1. Goal
To predict whether BTC to USD will go up or down on the next day based on the data from the previous day.
## 2. Dataset
Time series price data of BTC/USD, other currency pairs, market indices, commodities, stocks, and bonds on the same day as BTC/USD and the previous day, shown as “up”, “down”, or “equal”. For all the attributes and class attribute, “up” means the closing price of the day is higher than the closing price of the previous day. “down” means the opposite. “equal” when the two prices are equal. If the value is N/A, “equal” is put in.
To the best of my knowledge, the timings of closing are BTC/USD 18:00, Currency 18:00, Futures 17:00, Bond 17:00, and Stock 16:00.
## 3. Tools and Algorithms
- Tool
Waikato Environment for Knowledge Analysis (Weka) is used for this project. Weka is an open source machine learning software developed by University of Waikato, New Zealand.
- Algorithm
The attribute evaluators with search methods on Weka are utilized to select attributes from the dataset, and the classifiers to train models and make predictions.
## 4. Procedure, Evaluation and Results
Please view the report [here](https://github.com/eatingyeh/Objects_Classifiers/blob/main/Object%20Detection%20Classifier_Yi-Ting%20Yeh.ipynb) for more details.
