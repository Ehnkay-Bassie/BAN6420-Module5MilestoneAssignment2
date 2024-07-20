# Project: Principal Component Analysis
------------------------------------------

## Project Overview

- As a Data Analyst at the Anderson Cancer Center, the objective of this project is to develop a model to address the increasing number of referrals at the center. 
- The model's first step is to identify essential variables crucial for securing donor funding. 
- After consulting with the team, Principal Component Analysis (PCA) was selected as the most appropriate technique for this task. 
- Additionally, logistic regression is implemented for prediction purposes.
---------------------------------------------------

## Project Description

In this project, the following tasks are performed:

1. PCA Implementation:
   - Utilize PCA to identify essential variables from the cancer dataset available in 'sklearn.datasets'.
2. Dimensionality Reduction:
   - Reduce the dataset into two PCA components.
3. Logistic Regression:
   - Implement logistic regression for prediction using the reduced dataset.
-------------------------------------------------------------------

## Project Instructions

To successfully complete this project, follow these steps:
1. Implement PCA:
   - Load the cancer dataset 'load_breast_cancer' from 'sklearn.datasets'.
   - Standardize the data before applying PCA.
   - Perform PCA to reduce the dataset to two principal components.
2. Dimensionality Reduction:
   - Extract the first two principal components from the PCA result.
   - Visualize the reduced dataset.
3. Logistic Regression:
   - Implement logistic regression on the reduced dataset to create a prediction model.
   - Evaluate the model's performance.
----------------------------------------------------------------------------------

## How to Run the Notebook

1. Clone the Repository or download the file.

2. Install Dependencies:
   - Ensure that you have all the necessary Python libraries installed. You can install the required libraries using:
   'pip install numpy pandas scikit-learn matplotlib seaborn'

3. Run the Notebook:
   - Open and run the 'PCA_LogisticsRegression.ipynb' notebook using Jupyter Notebook or any compatible environment.

4. View Results:
   - Follow the instructions and code cells in the notebook to execute each step and view the results.
   - Run the code sequentially.
--------------------------------------------------------------------------------------------------------

## File Structure

- **PCA_LogisticsRegression.ipynb:** Jupyter notebook containing the complete analysis, including PCA implementation, dimensionality reduction, and logistic regression.
- **README.md:** This is the file you have open that gives detailed instructions on how to run the 'PCA_LogisticsRegression.ipynb' file.
----------------------------------------------------------------------------------------------------------------

## Conclusion

- This project demonstrates the use of PCA to identify essential variables and reduce dimensionality in a cancer dataset. 
- The implementation of logistic regression provides a prediction model using the reduced dataset. 
- The notebook includes detailed instructions and code to guide you through the entire process.
------------------------------------------------------------------------------------------
