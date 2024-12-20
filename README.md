# ML_predictions
This Project is all about predicted the production or yield of the crop. It mainly aims to predict the production or yield of crops based on climate change factors. We explore the impact of climate change on crop yields and develop a predictive model to forecast future yields. Majorly Random forest and ARDL model is used
# Features
Climate change factors- Temperature, precipitation, pesticide
Crop yield prediction- Predicting crop yields based on historical climate data and machine learning models.
# Technology used 
Programming language used: Python
Machine learning techniques used: Random forest and ARDL(Auto-regressive distributed lag)
Datavisualization library: Matplotlib
Data Storage: CSV
# Methodology
The project involves Random forest model,initially it's necessary to clean the data. The features must be noted including target variable
OneHotCoding is applied here, due to inconvenience where RF model refused to study string values. So it is necessary to convert it to float
Training and testings of sets are done with all ratios including 90:10, 80:20, 70:30, 60:40.
RandomforestRegressor trains the model to get accurate predictions

We used ARDL model also to predict the same. To know which model has good accuracy and more efficient in predicting yield. It starts with ADF test for each variable to know if it's stationary or not.
It is necessary to differentiate the variables into endogenous and exogenous to know which variables are dependent and to fit the model.
Check residuals for autocorrelation
Training the model is done with test splits 0.1, 0.2, 0.3 and 0.4.

The final confusion matrix and accuaracy are analyzed. According to all these models, the Random forest with 90:10 ratio/ 0.1 split has the accurate prediction. 


# Installation
Clone the repository:
   ```bash
   git clone https://github.com/Neharamesh31/ML_predictions.git
