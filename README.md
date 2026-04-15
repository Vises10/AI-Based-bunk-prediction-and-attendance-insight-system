# AI-Based Bunk Prediction & Attendance Insight System

## Overview
This project is a Data Science application that predicts whether a class is likely to be bunked using machine learning. It also provides insights into attendance patterns using data visualization.

---

## Objective
- Predict bunk behavior using attendance-related features  
- Analyze patterns in student attendance  
- Provide simple visual insights  

---

## Dataset
- Self-created dataset based on timetable and attendance  
- Contains 241 records  
- Features include:
  - Day, Subject, Teacher  
  - Interest Level  
  - Event Day, Test Day  
  - Previous Attendance Percentage  
  - Bunked (target variable)

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

## How It Works
1. The dataset is loaded and cleaned to remove inconsistencies.  
2. Categorical data is converted into numerical format using encoding.  
3. Important features are selected for model training.  
4. The dataset is split into training and testing sets.  
5. A Decision Tree model is trained on the training data.  
6. The model learns patterns from the data and makes predictions.  
7. The model is evaluated using accuracy and other metrics.  
8. Results are visualized using graphs for better understanding.

---

## Methodology
1. Data loading  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature selection and encoding  
5. Train-test split  
6. Model training (Decision Tree)  
7. Model evaluation  
8. Prediction and visualization  

---

## Model
- Decision Tree Classifier  
- Used for binary classification (Bunked: Yes/No)

---

## Results
- Model predicts whether a class will be bunked or not  
- Accuracy: ~55%  
- Generated insights using graphs:
  - Bunk pattern by day  
  - Bunk pattern by subject  
  - Attendance distribution  

---

## Sample Prediction
The model takes input features and predicts:
- Output: Yes / No (Bunked or Not Bunked)

---

## Future Scope
- Use larger dataset  
- Apply advanced models  
- Develop web/mobile application  

---

## Conclusion
This project shows how machine learning can be used to analyze and predict student attendance behavior using real-world data.

---

## References
- https://www.mdpi.com/2076-3417/10/9/3116  
- https://pmc.ncbi.nlm.nih.gov/articles/PMC12615791/  
- https://scikit-learn.org/  
- https://pandas.pydata.org/  

---

## Author
Vishesh Kr. Bachchas  
B.Tech CSE (1st Year)
