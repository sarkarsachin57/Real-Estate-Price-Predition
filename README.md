# Real-Estate-Price-Predition
![image](https://user-images.githubusercontent.com/83460431/133652384-30dd523e-60d2-4471-8e03-fbbf9cd4e34c.png)

##### Through this project I builded an end to end solution using Data Science and Machine Learning that can predict an approximate House prices for anywhere in India better than individuals. This project starts with importing data into python notebook and ends with deployment. Here are the steps coverd in this project. 

##### Importing Data : 
Through this module I import the dataset that I collected from Kaggle as well as the essentials libraries or APIs that are needed to manipulate next steps.
##### Data Exploration :
Through this module I explore the dataset to understand about the dataset, it's different features, shape, columns, data types, what the data about, classes in categories, detecting the missing values, outliers, etc..
##### Data Visualisation : 
Through this step I try to find few more deep insights on the data through visualize it. I use scatterplots, boxplots, distribution plots, bar plots to understand the patterns of the data, the relations among the attributes, their distribution, etc.
##### Data Transformation : 
Through this module I did Data Transformaton as the Machine Learning Algorithms don't process any dataset with strings, NaNs and data which is not in a well structure. I transform address data by split in the cities into it, remove dupicate records, remove outliers like over priced houses, handle those city records with lack of multiple records, encode categoricsal data to numeric etc.
##### Final Data Exploration ; 
Here in this step I just exploring the dataset again to chek that the dataset is completly ready to train a Machine Learning model properly or not.
##### Machine Learning Model Building :
In this part I trained multiple Machine Learning Models using Multiple Regression Algorithms like Linear Regression, Decision Tree, Random Forest, Support Vector, XGBoost, ADABoost, Bagging, KNearestNeighbours, Extra Tree, Gradient Boosting, Stacking, Voting etc. Then analyzing the perfomance or accuracy of each models and finally select Stacking Regression Model as it provides the best accuracy as RSquare score of 0.8278 (approx).
##### Model Deployment : 
In this part I devloped the final Web Application using Flask, HTML, CSS and deploy the Machine Learning Model that previously builded. And then I created product which looks like : 


![2021-10-18 (2)](https://user-images.githubusercontent.com/83460431/137752090-b18ccfb0-aa71-481f-88ab-820b991180bd.png)
![2021-10-18 (5)](https://user-images.githubusercontent.com/83460431/137752530-4e4f91b5-d75c-43bc-9659-9162f5433181.png)

