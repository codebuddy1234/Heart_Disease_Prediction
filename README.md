# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals take preventive actions and provide timely treatment.

This project develops a Machine Learning model to predict the presence of heart disease based on medical attributes such as age, cholesterol level, blood pressure, chest pain type, maximum heart rate, and other clinical factors.

The project covers the complete Machine Learning workflow including data preprocessing, feature engineering, model training, performance evaluation, and model comparison.

---

## 📊 Dataset Information

**Dataset Name:** Heart Disease Dataset

### Dataset Details

* Original Records: 1025
* Total Features: 14
* Duplicate Records Removed: 723
* Final Cleaned Records: 302
* Target Variable: `target`

### Target Classes

* `0` → No Heart Disease
* `1` → Presence of Heart Disease

### Dataset Features

| Feature  | Description                       |
| -------- | --------------------------------- |
| age      | Age of patient                    |
| sex      | Gender of patient                 |
| cp       | Chest pain type                   |
| trestbps | Resting blood pressure            |
| chol     | Cholesterol level                 |
| fbs      | Fasting blood sugar               |
| restecg  | Resting ECG results               |
| thalach  | Maximum heart rate achieved       |
| exang    | Exercise-induced angina           |
| oldpeak  | ST depression induced by exercise |
| slope    | Slope of peak exercise ST segment |
| ca       | Number of major vessels           |
| thal     | Thalassemia                       |
| target   | Heart disease prediction          |

---

# 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

# 🔄 Machine Learning Workflow

## 1. Data Loading & Preprocessing

* Loaded the heart disease dataset using Pandas.
* Checked dataset shape, information, and data types.
* Identified missing and duplicate values.
* No missing values were found.
* Removed 723 duplicate records.
* Split the dataset into training and testing sets (80:20).
* Applied StandardScaler for feature scaling.

---

## 2. Feature Engineering

* Performed correlation analysis using a heatmap.
* Calculated feature importance using Random Forest.
* Analyzed the contribution of each feature to the prediction task.
* Retained all relevant features for model training.

---

## 3. Machine Learning Models Implemented

The following classification algorithms were trained and evaluated:

### Logistic Regression

A statistical model used for binary classification problems.

### Decision Tree Classifier

A tree-based algorithm that creates decision rules from training data.

### Random Forest Classifier

An ensemble algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## 4. Model Evaluation Metrics

The models were compared using the following metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

The model with the best overall performance was selected as the final prediction model.

---

## 📈 Data Visualizations

The project includes:

* Correlation Heatmap
* Feature Importance Graph
* Confusion Matrix of the Best Model
* Model Performance Comparison Table

---

## 🎯 Project Outcome

This project successfully developed a Machine Learning-based heart disease prediction system. Different classification algorithms were compared, and the best-performing model was selected based on evaluation metrics.

The final model can assist in predicting heart disease risk and demonstrates the practical application of Machine Learning in the healthcare domain.

---

## 📁 Project Structure

```
Heart-Disease-Prediction/
│
├── Heart_Disease_Prediction.ipynb   # Complete ML analysis and model training
├── Data/heart.csv                   # Dataset file
├── README.md                        # Project documentation
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
[git clone https://github.com/codebuddy1234/Heart_Disease_Prediction.git
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Start Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open and Run Notebook

Open `Heart_Disease_Prediction.ipynb` and execute all cells sequentially.

---

## 👨‍💻 Author

**Lokesh Sapkale**
B.Tech (Artificial Intelligence & Machine Learning) Student

**Skills:**

* Python Programming
* Data Analysis
* Machine Learning
* SQL
* Data Visualization

---

## ⭐ Future Improvements

* Hyperparameter tuning for improving model performance.
* Deployment using Flask or Streamlit.
* Integration with a web-based healthcare prediction system.
* Using larger medical datasets for better generalization.

---

## 📜 License

This project is developed for educational and internship purposes.
