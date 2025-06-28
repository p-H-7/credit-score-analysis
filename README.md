# Credit Score Analysis & Prediction

This project analyzes customer financial data to predict credit scores (Good, Standard, Poor) using machine learning techniques. The system can help financial institutions automate credit assessment and make informed lending decisions.

## Key Components

### 1. Data Import & Setup
- Uses libraries like pandas, numpy, matplotlib, seaborn, scikit-learn, and XGBoost
- Loads a training dataset with 100,000 records and 28 features

### 2. Dataset Features
The dataset includes customer information such as:
- **Personal Info**: Customer ID, Name, Age, SSN, Occupation
- **Financial Data**: Annual Income, Monthly Salary, Bank Accounts, Credit Cards
- **Credit Behavior**: Interest Rate, Loan Details, Payment History, Credit Mix
- **Target Variable**: Credit Score (Good, Standard, Poor)

### 3. Data Cleaning Process
Extensive data preprocessing including:
- **Missing Value Handling**: Filling nulls with group modes
- **Outlier Detection**: Statistical methods to identify and clean outliers
- **Data Type Conversion**: Converting strings to appropriate numeric types
- **Categorical Cleaning**: Replacing garbage values (like '_', '#F%$D@*&8') with proper values

### 4. Exploratory Data Analysis
- Distribution analysis of all variables
- Visualization using count plots, histograms, and stacked bar charts
- Relationship analysis between features and credit scores

### 5. Machine Learning Models
The project appears to be set up for classification using:
- Decision Trees
- Random Forest
- Logistic Regression
- XGBoost
- Naive Bayes
- K-Nearest Neighbors
