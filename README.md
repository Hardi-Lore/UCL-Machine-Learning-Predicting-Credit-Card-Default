# Predicting Credit Card Default
![alt text](https://www.alliance4tech.eu/wp-content/uploads/2018/06/ucl.jpg)
## Practical Application of Machine Learning to a Real World Problem
**BENG0095 Assignment**  
*Dr. Dariush Hosseini (dariush.hosseini@ucl.ac.uk)*

**Overview**  
- Assignment Submission Date: 8th January, 2020
- Final Submission Format: Jupyter Notebook file

**Assignment Description**  
This assignment focuses on credit card default prediction, a common and important application of machine learning in finance. You will use data from the 'Default of Credit Card Clients' Data Set from the UCI Machine Learning Repository to build a machine learning model that predicts credit card default. The data is split into a training and a test dataset.

**Objectives**  
- Predict the default_payment_next_month variable (values: {0,1} indicating no default or default).
- Utilize training data and appropriate evaluation methods.
- Focus on the approach and understanding rather than just predictive accuracy.
- Be creative, engineer features, and seek inspiration from existing approaches.

**Data**  
Each data file are described below.
- CreditCard_train.csv: This file contains the data that you are to train and evaluate your model on. It consists of input and output data for the task. The features are as follows:

    - ID: The client id
    - X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family
    - (supplementary) credit
    - X2: Gender (1 = male; 2 = female).
    - X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
    - X4: Marital status (1 = married; 2 = single; 3 = others).
    - X5: Age (year).
    - X6 - X11: History of past payment: (The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above)
        - X6 = the repayment status in September, 2005
        - X7 = the repayment status in August, 2005
        - X8 = the repayment status in July, 2005
        - X9 = the repayment status in June, 2005
        - X10 = the repayment status in May, 2005
        - X11 = the repayment status in April, 2005.
    - X12-X17: Amount of bill statement: (NT dollar)
        - X12 = amount of bill statement in September, 2005
        - X13 = amount of bill statement in August, 2005
        - X14 = amount of bill statement in July, 2005
        - X15 = amount of bill statement in June, 2005
        - X16 = amount of bill statement in May, 2005
        - X17 = amount of bill statement in April, 2005.
    - X18-X23: Amount of previous payment: (NT dollar)
        - X18 = amount paid in September, 2005
        - X19 = amount paid in August, 2005
        - X20 = amount paid in July, 2005
        - X21 = amount paid in June, 2005
        - X22 = amount paid in May, 2005
        - X23 = amount paid in April, 2005
        - Y: The default outcome (0: No default, 1: Default)

- CreditCard_test.csv: This file contains the data that will be used to perform the final predictions which form part of your analysis.

**Getting Started**  
- Research existing approaches and aim for a novel solution.
- Use Python and existing libraries such as scikit-learn for key algorithms.

## Notebook Structure

### 1. Introduction
Provide an overview of the assignment, its objectives, and the dataset.

### 2. Data Import
Show how to import the data. Ensure that it can be easily replicated on another machine by changing data file locations.

### 3. Data Transformation and Exploration
Describe any data transformations, visualizations, and feature selection. Explain how you prepared the data for training.

### 4. Methodology Overview
Explain your methodology. Mention background research, feature engineering, and different approaches attempted.

### 5. Model Training and Validation
Detail how the model was trained and validated. Include any hyperparameter tuning, cross-validation, and performance metrics.

### 6. Results
Present the results obtained using your model on the training data. Compare different variations or approaches.

### 7. Final Predictions on Test Set
Demonstrate making final predictions on the test set using the trained model.

## Marking Guidelines

1. **Methodology (15%)**
   - Describe the methodology effectively.
   - Ensure its appropriateness for the task.
   - Go beyond simple application of classifiers.

2. **Evaluation Strategy (15%)**
   - Use a suitable evaluation strategy to avoid bias.
   - Explain how parameter values were chosen.
   - Include cross-validation if applicable.

3. **Presentation of Results (15%)**
   - Effectively present results on the training data.
   - Display results appropriately and clearly.
   - Provide insights into model performance.

4. **Interest of Approach (40%)**
   - Demonstrate an interesting and novel approach.
   - Apply unique data transformations or methods.
   - Avoid a standard classifier-only solution.

5. **Format, Structure, Referencing, and Clarity (15%)**
   - Ensure a well-structured notebook.
   - Include references for background research.
   - Maintain clear, error-free writing and well-commented code.



## License
This project is licensed under the MIT License - see the LICENSE file for details.


