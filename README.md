# 🎓 Student Performance Prediction using Logistic Regression

📊 This project analyzes student performance data using **Exploratory Data Analysis (EDA)** and applies **Logistic Regression** to predict student success based on various academic and social factors. The dataset is sourced from the **UCI Machine Learning Repository**.

## 📂 Project Features
- 📥 **Downloads and processes student performance data**
- 🔍 **Performs Exploratory Data Analysis (EDA) to understand key trends**
- 🛠 **Preprocesses categorical and numerical data**
- 🤖 **Applies Logistic Regression for classification**
- 📊 **Evaluates model performance using accuracy and classification reports**

## 📥 Installation & Setup
1️⃣ Clone this repository:
```bash
git clone https://github.com/your-username/student-performance-prediction.git
```
2️⃣ Navigate to the project folder:
```bash
cd student-performance-prediction
```
3️⃣ Install dependencies:
```bash
pip install requests zipfile pandas scikit-learn matplotlib numpy
```

## 📊 Dataset
The dataset is downloaded from the **UCI Machine Learning Repository** and includes two CSV files:
- 📄 **`student-por.csv`** (Portuguese students)
- 📄 **`student-mat.csv`** (Mathematics students)

Both datasets are combined for analysis.

## 🛠 Running the Project
Run the main script to preprocess data and train the model:
```bash
python student_analysis.py
```

## 🔍 Exploratory Data Analysis (EDA)
- 📋 **Displays first few rows using** `df.head()`
- 📊 **Provides summary statistics using** `df.describe()`
- ❓ **Checks missing values using** `df.isnull().sum()`
- 📌 **Examines data types and structure using** `df.info()`
- 📈 **Visualizes distribution of final grades (`G3`) using Matplotlib**

## 🤖 Model Training
- 🔧 **Preprocesses data, including encoding categorical variables and scaling numerical features**
- 📂 **Splits dataset into training and testing sets**
- 🏋️‍♂️ **Trains a Logistic Regression model to predict student performance**
- 📉 **Evaluates model accuracy and classification report**

## 📊 Example Output
- ✅ **Displays classification metrics such as accuracy, precision, and recall**
- 📉 **Plots histogram of student final grades (`G3`)**

## ⚙️ Configuration
Modify the dataset source or machine learning model in the script to experiment with different approaches.

## 🤝 Contributing
Feel free to **fork the repository** and submit **pull requests** with improvements.

## 📜 License
This project is licensed under the **MIT License**.

---
🌟 **Contributions are welcome!** Feel free to fork, modify, and submit a pull request.

