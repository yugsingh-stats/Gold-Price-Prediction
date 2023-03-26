Prediction of gold price using monthly dataset from January 1950 to July 2020

# Background

We have the data available of the above mentioned months. Initially, we start off the with the exploratory data analysis to discover patterns in the data with the help of graphical representations.

Next step was to calculate statistical metrics like coefficient of variation to help us understand the amount of risk an investor would take in comparison to the return they are expecting from their investment. 

Further we start off with the process of time-series analysis with training and testing the data- we trained 792 rows and tested 55 rows

Through linear regression modeling, we generated a graph representing the trained and tested data. 

Here, we observed that our mean absolute perecentage error came out to be as 29.76%.

Performing the final modeling using exponential smoothening metrics, we were succesfully able to lower our MAPE value to 17.24%, which was pretty satisfactory. 

Note: The lower the MAPE, the better the forecasting accuracy is. MAPE represents the average of the absolute percentage errors of each entry in a dataset to calculate how accurate the forecasted quantities were in comparison with the actual quantities.

Finally, we forecasted our data in the graph for further 10 years. 
