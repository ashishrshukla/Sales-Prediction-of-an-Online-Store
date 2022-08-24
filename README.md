# Sales-Prediction-of-an-Online-Store
It is very costly to maintain the inventry at the right time and fulfil the upcoming requirement from the customer. If a business can forcast the how much of each item it will sell in a month so that it can manage in a better way.

# Objective:
To forecast each item sales for an online retail store.

# Dataset:
The dataset has been taken from UCI Machine Learning Repository at:
https://archive.ics.uci.edu/ml/datasets/Online%20Retail

# Procedure
1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Modelling
6. Conclusion

# Result
The main aim of this project was to forcast the sales for each item in a month. The best performing algorithms are also overfitted, but that does not concern us much,
as despite overfitting, we are getting low RMSE for test dataset. Random Forest and Gradient Boost show the best performance on the test dataset.

![image](https://user-images.githubusercontent.com/104691416/186422153-4d590fa5-257b-431f-b76b-917cb1d26308.png)


In order to decide one of these, we look at the time taken in fitting the model. In all the algorithms, the prediction time was very small in comparison to the fit time.
Random Forest is taking much lesser time as compared to Gradient Boost. 
So we choose Random Forest as our final algorithm. Random Forest gives an RMSE of 22.7 on our test data.

	

	
	

	
	

	

