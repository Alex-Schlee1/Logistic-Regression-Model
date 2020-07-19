# Logistic Regression Model to analyze what kind of customers are most likely buying certain products

+ [Table of Contents](#sub-sub-heading-1)
    + [Credits](#credits)
    + [Project Goal and Procedure](#project-goal-and-procedure)
    + [Code and Resources](#code-and-resources)
    + [Part 1- Dataset Overview](#part-1--describing-the-dataset)
    + [Part 2- Data Insights](#part-2--data-insights)
    + [Part 3- Clustering the customers](#part-3--clustering-the-customers)
    + [Part 4- Deriving possible marketing strategies and conclusion](#part-4--deriving-possible-marketing-strategies-and-conclusion)


 ### Credits: 
 A big thank you goes to [KenJee](https://www.youtube.com/channel/UCiT9RITQ9PW6BhXK0y2jaeg), [Codebasics](https://www.youtube.com/channel/UCh9nVJoWXmFb7sLApWGcLPQ), [Krish Naik](https://www.youtube.com/user/krishnaik06), [Keith Galli](https://www.youtube.com/channel/UCq6XkhO5SZ66N04IcPbqNcw)  and to the whole [Edureka Team](https://www.youtube.com/user/edurekaIN) who put a lot of effort to teach people Data Science,Machine Learning, Statistics and a lot of other related topics for free.
 
 ### Project Goal and Procedure
 * Goal: Analyzing, based on different marketing campaigns, which customers are willing to buy certain banking products  
 * Algorithm: Logistic Regression
 * Using dataset from [Kaggle.com](https://www.kaggle.com/)
 * visualization of data using seaborn and matplotlib packages

 ### Code and Resources

* Python Version: 3.8
* Environment: Jupyter Notebook
* Packages: Pandas, Seaborn, Numpy, Scikit-learn

## Part 1- Dataset Overview
The dataset, which was taken from Kaggle.com(https://www.kaggle.com/) is showing different information about the customers. The data was collected during marketing campaigns.
Now the bank wants to analyze the data to be able to predict customers behaviour when new products are offered. 

So the main question is: Who is the potential customer, who can I target? 

In total, the dataset contains more than 40.000 data from different customers. Among others, we have information about the age, the job, the marital status, education, possession of a house or not, having a loan or not and so on.
Totally, we have 20 independent variables (features) and one dependent variable (target), which is the fact if a customer has bought a certain product (yes/no). I you are interested in getting more information what each independent variable means, you can take a look in the Github repository where the descriptions are provided:
<img src='./images/image1.PNG' width=400>

## Part 2- Data Insights
Data Visualization is always a good approach to get a better understanding of the data and its structure. 
The first plot shows a simple relation between the the number of people who bought a product and who did not. The result shows that 11% of the customers bought the product.


<img src='./images/image2.PNG' width=400>






