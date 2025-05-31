# Data Cleaning & Preprocessing : Titanic Dataset 

This project performs data preprocessing and exploratory analysis on the Titanic dataset. The goal is to clean and prepare the data for machine learning, and gain insights into the factors affecting passenger survival.

## Dataset

The dataset consists of information on passengers aboard the Titanic, including:
- Demographic details (Age, Sex)
- Ticket and fare data
- Class and cabin information
- Survival status

## Steps in the Analysis

### 1. Import and Initial Exploration
- Loaded the dataset using `pandas`.
- Inspected the shape, structure, and missing values.
- Observed missing data primarily in `Age`, `Cabin`, and `Embarked`.

### 2. Data Cleaning and Preprocessing
- **Cabin** column was dropped due to a large number of missing values.
- **Age** was imputed using the **median** value.
- **Embarked** was imputed with the **most frequent** port of embarkation.
- Categorical columns (`Sex`, `Embarked`) were encoded using `LabelEncoder`.

### 3. Feature Engineering 



### 4. Model Preparation 


## Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## How to Run

1. Clone this repository or download the notebook.
2. Ensure you have Python installed with the necessary libraries:
   ```bash
   pip install pandas scikit-learn jupyter
