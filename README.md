# Objectives
The objective of this project was to analyze an HR dataset that contained information on company employees. This was a supervised learning task, so each employee was already known to have churned or not. Using this information, it was my task to predict what features best predict churn in an employee.

# Background
The dataset is available in this repo and consists of variables describing each employee's: 
* Satisfaction level	
* Last evaluation score	
* Number of current projects
* Avg monthly hrs	
* Yrs with company
* Total number of work accidents
* Whether or not they had a promotion in the last 5 years	
* Department	
* Salary

About 24% of the employees were found to have churned.

# Methodology
1. Data discovery and understanding where the highest dependencies lie. 
2. Created compound variables to look for deeper dependencies.
3. Developed multiple models for analysis, including Decision Trees and Logistic Regression.
4. Applied the most successful model to a final prediction which was saved and output for later predictions.

# Outcomes/Conclusions
It was found that multiple compound variables were the best at predicting churn in this instance, which included satisfaction level, years with company, last evaluation and salary, and combinations thereof. The model chosen for the final predictor was a Decision Tree model that predicted the best Recall score of 97%. 

# Next Steps
1. Refine decision tree model - use model variables and potentially further compound variables. 
2. Refine presentation deck used. Stay tighter to goal, and improve aesthetics for intended audience.
