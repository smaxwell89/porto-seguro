# Kaggle's Porto Seguro Safe Driver Challenge

Using the data provided by Brazil’s largest auto and homeowner insurance company Port Seguro, we used bagging and boosting methods to create models to predict the probability of a driver initiating an automotive insurance claim within the next year. Keeping the cost of insurance affordable relies on the accuracy of these predictions and over the past 20 years, Porto Seguro has relied on various machine learning techniques but are seeking more accurate models to ensure the affordability of their insurance.

Data Description
The data for the Porto Seguro’s Safe Driver Prediction competition is from the [Kaggle website](https://www.kaggle.com/c/porto-seguro-safe-driver-prediction/overview/evaluation). The “target” columns within both data sets, indicate whether or not a claim was filed by the policy holder and takes binary values of 0 for no and 1 for yes. Both the training and testing datasets, there are several variables included however, they are not named. Instead, the features that belong to the same groups are identified as “ind”, “reg”, “car”, and “calc” and have prefixes of bin for binary features or cat for categorical features. There are 3 “reg” variables, 15 “car” variables with 11 being categorical, 18 “ind” variables, 3 of which are binary and 11 being categorical, and 20 “calc” variables with 6 being binary variables. 
