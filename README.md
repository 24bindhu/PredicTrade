# PredicTrade



This project focuses on predicting the next-day movement of a stock index using machine learning algorithms. It demonstrates the full data science workflow — from raw historical data to predictive modeling and evaluation — using Python and its data science libraries.

Project Overview
Goal: Forecast whether the stock index will go up or down the next day.

Tech Stack: Python, Pandas, NumPy, scikit-learn

Models Used: Random Forest, Decision Tree, K-Nearest Neighbors (KNN)

Input Data: Historical stock market data (e.g., S&P 500) with features like Open, High, Low, Close, and Volume


Workflow
**Data Loading:**
Handled using a custom DataLoader class to read and format CSV data.

**Preprocessing & Feature Engineering:**

Calculated daily returns

Added moving averages (5-day and 10-day)

Created binary classification labels (price up or down)

**Model Training:**
Trained multiple models to classify future price movements based on historical indicators.

**Evaluation:**
Measured performance using:

Accuracy

Precision

Recall

F1-score

**Modular Code Design:**
Structured using object-oriented principles for clean, scalable code — ready for larger datasets or additional models.


**Key Takeaways**
Applied core machine learning techniques to real-world financial data

Built reusable data pipelines using object-oriented Python

Developed interpretable and scalable models for financial forecasting

Gained insights into model performance using standard classification metrics

