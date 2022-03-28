# Gold-Price-Prediction-Uisng-Python
This project is aimed at predicting the price of gold using Machine Learning Models and Algorithms. R-Squared Error has been used as an evaluation metrics whose value is the range of 0.9892 - 0.9902.
# Project Overview
Gold is a yellow metallic element that occurs naturally in pure form and is used to make coins, jewellery, etc.  In the past gold was used as a form of currency in many countries including USA. In the present time, it is a very precious form of metal and the abundant quantity of gold is kept in reserve with the central banks of the respective countries which is used for re-payment of foreign debt, controlling the inflation and other related activities which reflects in financial strength of the country. In the recent times developing countries such as India, China and Russia have emerged out to be the largest buyers of gold in the international market. On the other hand, countries like USA, South Africa and Australia have emerged out to be the largest seller of gold. Thus, the demand and supply of gold in all types of market play an important role in deciding it’s price. However, apart from Demand and Supply there are many other factors as well that helps in deciding the price of gold such as prices of other precious metals, prices of crude oil, performance of the stock market, Bonds etc.

In this project, I have forecasted the gold rates using the most comprehensive set of features and used machine learning algorithms for forecasting the gold rates and compare the result. For this project I have used “Gold Price Data” that I downloaded from https://www.kaggle.com/altruistdelhite04/gold-price-data where the data ranges from 01-02-2008 to 05-16-2018. There is total 2290 rows and 6 columns. The names of the column is Date, SPX, GLD, USO, SLV, EUR/USD respectively. I have tried to predict the price of gold with respect to the corresponding rows in other columns. Here I have used Random Forest Regressor Machine learning model to predict the price of the gold.

Graph showing how close the Actual Gold Price and the Predicted Gold Price is:
![gold](https://user-images.githubusercontent.com/74102049/160405073-9fac856f-f9c5-49e7-8e62-c08b068e96bb.jpg)
# Project Workflow
![Gold price workflow diagram](https://user-images.githubusercontent.com/74102049/160400436-1f5f1af2-84a8-40b4-a123-8cda15cc927d.jpeg)

# Problem Highlighted
The Goal of this project is to accurately predict the price of Gold Price (GLD) across a given period of time in the future. In this project I have used Random Forest Regressor Model Machine Learning Algorithm to predict the future price of Gold.

During this Project I have learnt following things:

  •	How to apply machine learning techniques, models and algorithms on a dataset.

  •	How to perform Exploratory Data Analysis (EDA) on a dataset.

  •	How to collect and pre-process the data.

  •	How to apply the different machine learning models on the dataset and analyse the model’s performance.

  •	How to optimize the machine learning model and increase it’s accuracy and reduce the error.
  
 # Required Installations  
Following installations are required in order to run the project

•	Python 3.x

Following Libraries are used in this project

•	Numpy

•	Pandas

•	Seaborn

•	Matplotlib

•	Scikit-Learn

Apart from this I would also recommend to download Anaconda which contains all the pre-packaged Python Libraries and the necessary software such as Jupiter Notebook. This project is built using the Jupiter Notebook.

# Code:
The entire code is provided in one file  Gold_Price_Prediction.ipynb.
Apart from this a PDF of the Jupiter notebook file is also uploaded in this project Repository for reference.

# Evaluation Metrics:
 In this project I have used R Square Error or R2 Score as my evaluation metrics. R2 Score is a statistical measure that shows how close the data are towards the fitted regression line. Or in other words it calculates how accurately the model can predict the correct value. It is also known as the coefficient of determination.
 
R-squared is always between the range 0 – 100 %:

•	0% indicates the model shows that there is no variability of the response data around its mean.

•	100 % indicates that the model explains the variability of the response data around its mean.

Thus Higher value of R2 Score shows that the difference between the Actual Value and the Predicted Value is less which in turns show that our model gives accurate results.

# Other Graphs of this project
![Gold 1](https://user-images.githubusercontent.com/74102049/160408443-5bfb9727-904c-497b-a6ed-527aaa6dd79a.jpg)
![Gold 2](https://user-images.githubusercontent.com/74102049/160408459-a4156f1f-e0e1-403b-9a8d-523cc6041ec4.jpg)

From this graph it can concluded that Silver Feature is linearly progressing with gold feature.

![Gold 3](https://user-images.githubusercontent.com/74102049/160408475-37dfab44-c74f-497c-8e89-c8a73c1317c5.jpg)

From this graph it can be concluded that feature USD and SPX have Outliers.

![Gold 4](https://user-images.githubusercontent.com/74102049/160408491-8bb99382-f7d0-4644-8e96-9f0119abd8f4.jpg)

This Graph shows the correlation between the different features in the dataset.

![Gold5](https://user-images.githubusercontent.com/74102049/160408540-8e551aec-8549-4fd6-a81c-1568d14a109e.jpg)
