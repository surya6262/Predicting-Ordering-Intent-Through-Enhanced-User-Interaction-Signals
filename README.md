# Predicting Ordering Intent Through Enhanced User Interaction Signals
- Overview
    This project focuses on predicting customer purchasing intent on an e-commerce platform using Machine Learning techniques. The system analyzes user interaction behavior such as page views, time spent on pages, bounce rates, exit rates, and browsing patterns to determine whether a user is likely to make a purchase.
    The project helps businesses understand customer behavior and improve marketing strategies, personalized recommendations, and conversion rates.

#   Problem Statement 
    Using data that simulates real-world e-commerce interactions, the classification system is trained on features like session duration, click-through rate, referral source, and membership status. The goal is to develop a robust machine learning model capable of accurately identifying users with a high purchase intent.

## Dataset
- Dataset Used:
  Online Shoppers Intention Dataset
    Target Column: MadePurchase
    Features Include:
    Account pages viewed
    Product pages viewed
    Information pages viewed
    Time spent on pages
    Bounce rate
    Exit rate
    Page value
    Visit month
    Browser type
    Operating system
    Traffic source
    Weekend visit indicator

## Technologies Used
- Programming Language:
    Python
  # Libraries:
    Pandas
    NumPy
    Matplotlib
    Seaborn
    Scikit-learn
 
#   Machine Learning Models:
    Logistic Regression
    Decision Tree Classifier
    Random Forest Classifier 

# Project Workflow
1. Data Collection
    Imported dataset using Pandas.
2. Data Preprocessing
    Checked missing values
    Handled categorical variables
    Label encoding
    Feature scaling using StandardScaler
3. Exploratory Data Analysis
    Correlation analysis
    Heatmap visualization
    Feature importance analysis
4. Model Building
    Implemented and trained:
    Logistic Regression
    Decision Tree
    Random Forest
5. Model Evaluation
    Compared models using:
    Accuracy Score
    Graphical comparison using bar charts

## Results
    Random Forest achieved the best performance among the tested models.
    The project successfully predicts customer ordering intent based on user interaction signals.

## How to Run the Project
1. Step 1: Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

2. Step 2: Run Jupyter Notebook
jupyter notebook

3. Step 3: Open the notebook and execute all cells.
├── dataset/
│   └── online_shoppers_intention.csv
│
├── notebooks/
│   └── prediction_model.ipynb
│
├── README.md