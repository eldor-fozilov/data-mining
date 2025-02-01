# Income Classification Project

This project predicts whether an individual's annual income is above or below $50,000 using various features such as age, education level, gender, and occupation. The analysis, preprocessing, modeling, and evaluation steps are detailed in the `finalproject.ipynb` notebook.

## Repository Structure
- `data/`: Contains the dataset used for the project.
- `finalproject.ipynb`: Jupyter notebook with code for data analysis, preprocessing, and model training.
- `finalreport.pdf`: Detailed report summarizing the project, including hypotheses, methodologies, results, and conclusions.

## Project Overview
1. **Problem Statement**: Classify individuals based on their annual income using demographic and work-related features.
2. **Hypotheses**:
   - Age, education level, gender, and sector are significant predictors of income.
   - Higher education and age correlate positively with income.
3. **Methodology**:
   - **Exploratory Data Analysis (EDA)**: Analyzed feature distributions and relationships with income.
   - **Preprocessing**: Handled missing values, outliers, and imbalanced data. Performed one-hot encoding and feature scaling.
   - **Modeling**: Trained and evaluated three models (KNN, Logistic Regression, Random Forest) using stratified 10-fold cross-validation.
   - **Hyperparameter Tuning**: Used RandomizedSearchCV to optimize model performance.

## Results
- **Best Model**: Random Forest showed the best overall performance with high ROC and F1 scores.
- **Key Features**: Education level, age, and occupation were the most influential predictors.

## Conclusion
The project validated the hypotheses and identified key factors influencing income classification. For details, refer to the [final report](finalreport.pdf).
