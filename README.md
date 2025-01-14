# Car-Evaluation-Database-using-Decision-Trees
This project utilizes the Car Evaluation Database, a dataset designed to evaluate the acceptability of cars based on various features.
The project focuses on implementing and comparing machine learning models, specifically Decision Trees and Logistic Regression, to predict car acceptability.

**Dataset Information**

The dataset contains 1728 instances and 6 attributes with no missing values. The columns in the dataset are as follows:

**Feature Description**

buying - Buying price of the car (categorical: v-high, high, med, low).

maint - Maintenance cost (categorical: v-high, high, med, low).

doors -Number of doors (numeric).

persons - Passenger capacity (numeric).

lug_boot - Size of luggage boot (categorical: small, med, big).

safety - Estimated safety rating (categorical:low, med, high).

Target Classes:

unacc (unacceptable): 70.023% 

acc (acceptable): 22.222% 

good: 3.993% 

v-good (very good): 3.762% 

**Objective**

The primary objective is to develop a Decision Tree model to classify student performance into one of the four classes (unacc,acc,good,v-good) and identify the key factors influencing these classifications.

**Project Workflow**

**Data Preprocessing:**

Encoded categorical variables.

Split data into training and testing sets.

**Model Selection:**

Implemented Decision Trees,Logistic Regression and some models.

Compared performance metrics such as accuracy, precision, recall, and F1-score.

**Results:**

Decision Trees achieved the best accuracy for predicting car acceptability compared to other models.

**Visualization:**

Confusion matrices and decision tree diagrams were generated to interpret the model performance.

---------------------------------------------------------------------------------------------------------

**Key Insights**

Decision Trees performed better due to their ability to capture non-linear relationships and hierarchical decision-making processes.

**Technologies Used**

**Programming Language:**

Python

**Libraries:**

pandas for data manipulation.

numpy for numerical computations.

matplotlib and seaborn for data visualization.

**Future Work**

Explore advanced machine learning models such as Random Forest, Gradient Boosting, or Neural Networks to improve accuracy.

Identify and rank the most influential features affecting car acceptability.

**Contributing**

Contributions are welcome! Please fork the repository and submit a pull request.

