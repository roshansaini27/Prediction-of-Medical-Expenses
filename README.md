## Prediction-of-Medical-Expenses
Based on the survey data Linear regression model is developed to predict medical expenses. 
It helps insurance companies to estimate insurance premiums based on model features like age, BMI, region, gender etc.
### Objective:
This model is developed to predict annual medical expenses of a person based on certain charcterstics so that the insurance companies can charge premium accordingly
### Data information:
age - Age of the person (numeric)

Gender - Gender of the person (binary: male or female)

bmi - The body mass index (BMI) of the person (numeric)

children - Number of children the person have (integer

smoker - Does the person smoke or not (binary: yes or no)

region - Region the person belongs to (categorical)

expenses - Annual medical expenses of the person (numeric)
### Table of Contents:
* Import & Read data
* Data review & check
* Descriptive Statistics
* Train test split 
* Exploratory data analysis
* Outliers handling
* Missing value imputation
* Model development (OLS)
* Conclusion
### Technologies:
This project is created with:
* Jupyter Notebook
* Python
* Python Libraries: Pandas, NumPy, matplotlib, SciPy, Seaborn, Scikit Learn
### Result: 
* For Train data: * RMSE: 6169.692 * R2 Score: 0.745
* For Test data: * RMSE: 7552.864 * R2 Score: 0.594
* R Square of Train data is 0.745 but the same model is underperforming with test data and giving R square only 0.594
* It indicates that model is overfitting on train data (able to explain the variance of train data but not able to explain variance of test data)
* This model needs to further investigate to remove overfitting
### Future Work
* To remove the overfitting, we will perform K fold cross validation and develop the model again


### Exploratory data Analysis
![image](https://user-images.githubusercontent.com/101332838/184523809-6ce5ee1e-5076-4b84-8596-311bdcd3a12d.png)
![image](https://user-images.githubusercontent.com/101332838/184523812-6576a96b-4714-4f9a-9f0d-e83038768529.png)
![image](https://user-images.githubusercontent.com/101332838/184523821-1af6beae-fee1-47f7-b79f-f110f33a2bc6.png)
![image](https://user-images.githubusercontent.com/101332838/184523828-bc28d16c-4db9-48b2-b545-1dc2c5339d1e.png)
![image](https://user-images.githubusercontent.com/101332838/184523839-fa16b396-6773-458a-a33c-7ebb55171106.png)

