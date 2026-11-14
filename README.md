# 🎓 Student Performance Prediction using Machine Learning

## 📌 About the Project

This project focuses on predicting students' examination scores using Machine Learning techniques.

It uses a **Linear Regression model** to understand the relationship between the number of hours a student studies and their expected examination score.

The project is implemented using Python in Google Colab and demonstrates the basic workflow of building a Machine Learning model.

## 🎯 Objectives

- Understand and explore student performance data.
- Perform basic data analysis and visualization.
- Identify the relationship between study hours and exam scores.
- Build and train a Linear Regression model.
- Predict examination scores based on study hours.
- Compare actual and predicted examination scores.

## 📊 Dataset

The project uses the Student Performance Factors dataset.

- Total Records: 6,607
- Total Features: 20
- Target Variable: Exam_Score
- Input Feature used for prediction: Hours_Studied

The dataset contains information about study hours, attendance, parental involvement, sleep hours, previous scores, motivation level and other factors related to student performance.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 🤖 Machine Learning Algorithm

**Linear Regression**

Linear Regression is used to predict examination scores based on the number of hours students spend studying.

### Model Workflow

1. Import the required Python libraries.
2. Upload and load the dataset.
3. Explore and analyse the dataset.
4. Select the input feature (Hours_Studied).
5. Select the target variable (Exam_Score).
6. Split the dataset into training and testing sets.
7. Train the Linear Regression model.
8. Generate predictions.
9. Compare actual and predicted scores.
10. Predict scores for new study-hour inputs.

## 📈 Model Training

The dataset is divided into:

- 80% Training Data
- 20% Testing Data

The model learns from the training data and uses the testing data to generate predictions.

## 💻 How to Run the Project

1. Open the Jupyter Notebook in Google Colab.
2. Upload the `StudentPerformanceFactors.csv` dataset when prompted.
3. Run the notebook cells sequentially.
4. The model will train and generate predicted examination scores.
5. Enter the number of study hours to obtain a predicted score.

## 📂 Project Structure

```text
Student-Performance-Prediction-ML/
│
├── StudentPerformancePrediction.ipynb
├── StudentPerformanceFactors.csv
└── README.md
```

## 🌟 Learning Outcomes

Through this project, I explored:

- Data handling using Pandas.
- Data analysis and visualization.
- Understanding Machine Learning workflows.
- Training a Linear Regression model.
- Making predictions using trained models.
- Comparing actual and predicted values.

## 🔮 Future Improvements

- Use multiple student-related factors as input features.
- Experiment with different Machine Learning algorithms.
- Improve prediction performance through feature engineering.
- Develop an interactive student performance prediction application.

---

**Project Category:** Machine Learning | Data Science

**Language:** Python
