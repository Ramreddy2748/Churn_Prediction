# Churn_Prediction-using-_different_models

## Overview

This repository contains code and resources for a churn prediction project. The goal of this project is to predict customer churn using machine learning techniques.



**The ML Pipeline that I have followed is :**
  Importing the necessary libraries and the dataset
  Performing Data Preprocessing (Exploratory Data Analysis and Data Manipulation)
  Modelling using **Decision Tree,Random Forest, XGBoost**(Extreme Gradient Boosting)
  Performing Prediction
  Visualization of data

  
**FEATURES EXPLINATION**

**Row**: Represents the row number or an identifier for each record in the dataset.
**Id**: Likely an identifier for each customer or record.
**Surname**: The surname or last name of the customer.
**Score**: A numerical score, which could be related to credit score or some other form of customer evaluation.
**Nationality**: The nationality of the customer, indicating their country of origin.
**Gender**: The gender of the customer, typically represented as 'Male' or 'Female'.
**Age**: The age of the customer, indicating the number of years.
**Tenure**: The duration of the customer's relationship with the bank or service provider, often measured in years.
**Balance**: The financial balance or amount of money in the customer's account.
**Products**: The number of financial products or services the customer has with the institution.
**Card**: Presence of a card (e.g., credit card) associated with the customer.
**Active**: Indicates whether the customer is currently active or not.
**Salary**: The salary of the customer, representing their income.
**Exited**: A binary indicator (likely 0 or 1) that signifies whether the customer has exited or churned (1) or not (0).



**VISUALIZING DATA**

**Plot 1**:
The count plot will display bars for each unique category in the '**Gender**' column of the DataFrame. There will be one bar for each unique gender category, and the height of each bar represents the count of occurrences of that gender in the dataset.
This type of plot is useful for visualizing the distribution of a **categorical variable**, in this case, the distribution of genders in the dataset. It provides a quick visual summary of the number of occurrences of each category, making it easy to compare the counts between different categories.

**Plot 2**
The count plot will show a bar for each unique category in the '**Nationality**' column of the DataFrame. The height of each bar represents the count or frequency of occurrences of that nationality in the dataset.

**Plot 3**
plt.figure(figsize=(16,16)): This line of code is using **Matplotlib**, and it sets the **size of the figure** that will contain the count plot. The figsize parameter specifies the width and height of the figure in inches. In this case, it's set to 16 inches by 16 inches.
sns.countplot(data=df, x='Age'): This line of code creates a count plot using **Seaborn.** It specifies that the **'Age'** variable should be plotted on the **x-axis**, and the count plot will display bars for each unique age in the 'Age' column of the DataFrame df.

**Plot 4**
The plot will be a histogram of the '**Cibil Score**' variable with 20 bins. A **histogram** is a graphical representation of the distribution of a dataset. Each bar in the histogram represents the frequency or count of values falling within a specific range or bin.
This type of visualization is useful for understanding the distribution of a **numerical variable**, in this case, the distribution of scores. 

**Plot 5**

The resulting **bar chart** will visually represent the **accuracy scores of the three models**, making it easy to compare their performance. The color-coded bars provide a clear visual distinction between the models, and the y-axis indicates the accuracy values.

we can see that **three models** are being compared: XGBoost, Decision Tree, and Random Forest. The accuracy scores for each model are stored in the list accuracy_scores. To determine which model has the highest accuracy, you can find the maximum value in the accuracy_scores list.

**XGBoost** has the highest accuracy among the three models with an accuracy of **85**%. XGBoost is a popular and powerful machine learning algorithm known for its performance in various tasks.
