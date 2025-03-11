# Student Performance Prediction using Logistic Regression

## Overview
This project analyzes student performance data using **Exploratory Data Analysis (EDA)** and applies **Logistic Regression** to predict student success based on various academic and social factors. The dataset is sourced from the **UCI Machine Learning Repository**.

## Features
- **Downloads and processes student performance data**
- **Performs Exploratory Data Analysis (EDA)** to understand key trends
- **Preprocesses categorical and numerical data**
- **Applies Logistic Regression for classification**
- **Evaluates model performance using accuracy and classification reports**

## Installation
To run this project, install the required dependencies:

```bash
pip install requests zipfile pandas scikit-learn matplotlib numpy
```

## Dataset
The dataset is downloaded from the **UCI Machine Learning Repository** and includes two CSV files:
- **`student-por.csv`** (Portuguese students)
- **`student-mat.csv`** (Mathematics students)

Both datasets are combined for analysis.

## Running the Project
To execute the analysis, run:

```bash
python student_analysis.py
```

## Exploratory Data Analysis (EDA)
- **First few rows displayed** using `df.head()`
- **Summary statistics** provided using `df.describe()`
- **Missing values checked** using `df.isnull().sum()`
- **Data types and structure examined** using `df.info()`
- **Distribution of final grades (`G3`) visualized** using Matplotlib

## Model Training
- **Data preprocessing** includes encoding categorical variables and scaling numerical features
- **Splits dataset into training and testing sets**
- **Trains a Logistic Regression model** to predict student performance
- **Evaluates model accuracy and classification report**

## Example Output
- Displays **classification metrics** such as accuracy, precision, and recall
- Plots **histogram of student final grades (`G3`)**

## Configuration
Modify the dataset source or machine learning model in the script to experiment with different approaches.

## Contributing
Feel free to **fork the repository** and submit **pull requests** with improvements.

## License
This project is open-source and available under the **MIT License**.

