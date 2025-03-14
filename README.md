# Data Analysis | Undertanding results from a Stock Price Prediction database

## Project goal:
To understand the behavior and reliability of the predictions made by a Deep Neural Network model about Petrobras' (PETR4) stock price. 
This project showcases my abilities at: 
- Bringing relevant insights with data analysis 
- Python
- Statistics
- Finances

## Tools used:
Python (Pandas, Numpy, Matplotlib, Seaborn, Statistics, Scipy)

## Results and Conclusion:
The most reliable predictions are the ones for the next day (D_1) and for the next year (D_364), with the best results being present in the model trained with data from 2006 until the end of 2023. This conclusion is based on:

- D_1 and D_364 having the smaller means and standard deviations in the diference from the predicted and real observed price
- Smaller interquatile range and outliers for those predictions
- Hypothesys test proved the smaller standard deviation of the 2023 dataset over the other
