# Student Performance Prediction using Linear & Lasso Regression

## Project Overview

This project predicts **student academic performance** using machine learning regression models.
The model analyzes various student-related factors and predicts the **final performance score**.

Two regression algorithms were used:

* **Linear Regression**
* **Lasso Regression**

The project demonstrates how machine learning can be used to analyze educational data and predict outcomes based on different student attributes.

---

## Dataset

The dataset contains information about students and factors affecting their academic performance.

### Example Features

Typical features may include:

| Feature                     | Description                         |
| --------------------------- | ----------------------------------- |
| gender                      | Student gender                      |
| parental_level_of_education | Parent education level              |
| lunch                       | Type of lunch                       |
| test_preparation_course     | Completed preparation course or not |
| math_score                  | Math score                          |
| reading_score               | Reading score                       |
| writing_score               | Writing score                       |

The target variable represents the **student's performance score**.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook / Python Script

---

## Machine Learning Models

### Linear Regression

A basic regression algorithm that models the relationship between independent variables and the target variable.

### Lasso Regression

Lasso regression adds **L1 regularization**, which helps:

* Reduce overfitting
* Perform feature selection
* Improve model generalization

---

## Project Workflow

1. Import required libraries
2. Load the dataset
3. Data preprocessing
4. Feature encoding (if categorical variables exist)
5. Train-test split
6. Model training
7. Model evaluation
8. Prediction

---

## Model Evaluation

The models are evaluated using regression metrics such as:

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **R² Score**

These metrics help measure how accurately the models predict student performance.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/student-performance-prediction.git
```

Install required libraries:

```bash
pip install pandas numpy scikit-learn
```

Run the project:

```bash
python student_performance_prediction.py
```

---

## Project Structure

```
student-performance-prediction
│
├── student_performance.csv
├── student_performance_prediction.py
├── notebook.ipynb
└── README.md
```

---

## Results

Both **Linear Regression** and **Lasso Regression** models were trained and compared to evaluate prediction performance.

The comparison helps understand how **regularization affects model accuracy and feature importance**.

---

## Future Improvements

* Add more regression models (Ridge, Random Forest Regressor)
* Perform deeper feature engineering
* Add visualization for data analysis
* Deploy the model as a web application

---

## Author

Tushar Garg

GitHub: https://github.com/Tushar03garg
