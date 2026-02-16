# Major-Project
#Heart Disease (CVD) Prediction Project
This project focuses on predicting the risk of cardiovascular disease using patient data. The goal is to clean the dataset, explore important patterns, visualize relationships between features, and build machine learning models that can identify whether a person is likely to have heart disease.

#Project Objectives
Perform data preprocessing on the CVD dataset
Create visualizations to understand the features
Show the correlation matrix
Compare multiple machine learning models
Select the best model and prepare it for final prediction

#Steps Performed
1. Data Preprocessing
Loaded and cleaned the dataset
Dropped unwanted columns
Converted age into years
Fixed gender values
Checked and removed missing values
Encoded categorical features
Scaled numerical columns
Split the data into train, validation, and test sets

2. Exploratory Data Analysis
Histograms for all numerical columns
Count plot for target classes
Boxplots for distribution checks
Pairplots for feature comparison
Correlation heatmap for understanding relationships

3. Model Training
The following models were trained and evaluated:
Logistic Regression
K Nearest Neighbors
Decision Tree
Random Forest
Support Vector Machine

#Performance was compared using:
Accuracy
Classification report
Confusion matrix

4. Selecting the Best Model
#The model with the highest validation accuracy was chosen

Tested on the test set
Plotted the final confusion matrix
Plotted the ROC curve
Extracted feature importance if applicable
Saved the best model and scaler

5. Final Output
This project delivers:

Cleaned and processed dataset
Visual insights
Comparison of multiple models
A final trained model for CVD prediction
A user function to make future predictions

##Project Files
Jupyter notebook with the entire workflow

##Dataset file
Saved model and scaler files

##How to Run
Install required libraries
Open the notebook
Run all the cells in order
The graphs, results, and final predictions will be generated automatically

##Future Improvements
Add more medical features
Try deep learning models
Convert the model into an API or a web app
Create a dashboard for doctors or hospitals
