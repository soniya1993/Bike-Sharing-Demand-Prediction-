# Seoul-Bike-Sharing-Demand-Prediction

# Problem Statement

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# Data Description:

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Attribute Information:
• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)
# Data Wrangling

After loading our dataset, we observed that our dataset has 381109 rows and 12 columns. We applied a null check and found that our data set has no null values. Further, we treated the outliers in our dataset using a quantile method. 

image

# Data Pipeline:

● Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.

● Data Processing: In this part we went through each attributes and encoded the categorical features.

● Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

![image](https://user-images.githubusercontent.com/97510475/180387453-05d147b9-03f1-4ae2-a177-ae34326c927f.png)


# Metrics Evaluation

To evaluate our model and to obtain the accuracy and error rate of our models before and after hyperparameter tuning. We used some metric evaluation technique. They are:

i. Confusion Matrix

ii. Accuracy

iii. Precision

iv. Recall

v. F1-Score

vi. ROC-AUC Score

Observations:
● Observation 1: In the Model Evaluation Matrices table, Linear Regression, is not giving great results.

● Observation 2: Random forest performed good in terms of RSquare as compared to any other model.

# Conclusions:

● We started with loading the data, then we did Exploratory Data Analysis (EDA), null values treatment, feature selection, encoding of categorical columns, and then model building. In all of these models, our accuracy ranges from 56% to 91%, which can be said to be good for such a large dataset. This performance could be due to various reasons like the proper pattern of data, large data, or because of the relevant features.

● After performing variable importance analysis to find the most significant variables for all the models developed with the given data sets. We are getting the best results from Random Forest
