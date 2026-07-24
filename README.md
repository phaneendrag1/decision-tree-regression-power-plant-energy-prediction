# Decision Tree Regression – Power Plant Energy Output Prediction

## 📌 Project Overview

This project demonstrates the implementation of **Decision Tree Regression** using **Python** and **Scikit-learn** to predict the electrical energy output of a Combined Cycle Power Plant.

The model learns the relationship between environmental conditions and the plant's power output, providing accurate predictions using a Decision Tree Regression algorithm.

---

## 📊 Dataset

This project uses the **Combined Cycle Power Plant** dataset containing **9,568 observations**.

### Features

| Feature | Description |
|---------|-------------|
| AT | Ambient Temperature |
| V | Exhaust Vacuum |
| AP | Ambient Pressure |
| RH | Relative Humidity |
| PE | Electrical Energy Output (Target Variable) |

Dataset File:

```
Data.csv
```

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Project Workflow

- Import the required libraries
- Import the dataset
- Split the dataset into training and testing sets
- Train the Decision Tree Regression model
- Predict power output
- Evaluate model performance
- Visualize Actual vs Predicted values

---

## 🌳 Model

**Algorithm Used**

- Decision Tree Regression

**Target Variable**

- PE (Electrical Energy Output)

---

## 📷 Project Screenshots

### 1. Importing the Libraries

![Import Libraries](images/01_importing_libraries.png)

---

### 2. Dataset Import

![Dataset Import](images/02_dataset_import.png)

---

### 3. Splitting the Dataset into Training and Test Sets

![Train Test Split](images/03_train_test_split.png)

---

### 4. Model Training

![Model Training](images/04_model_training.png)

---

### 5. Power Output Prediction

![Prediction](images/05_power_prediction.png)

---

### 6. Model Evaluation

![Model Evaluation](images/06_model_evaluation.png)

---

### 7. Decision Tree Visualization

![Decision Tree Visualization](images/07_decision_tree_visualization.png)

---

## 📂 Repository Structure

```
decision-tree-regression-power-plant-energy-prediction/
│
├── Data.csv
├── decision_tree_regression_power_plant_energy_prediction.ipynb
├── README.md
├── requirements.txt
└── images/
    ├── 01_importing_libraries.png
    ├── 02_dataset_import.png
    ├── 03_train_test_split.png
    ├── 04_model_training.png
    ├── 05_power_prediction.png
    ├── 06_model_evaluation.png
    └── 07_decision_tree_visualization.png
```

---

## 📊 Model Evaluation

The model performance can be evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Compare with Support Vector Regression (SVR)
- Compare with Random Forest Regression
- Perform feature importance analysis
- Improve prediction accuracy through parameter optimization

---

## 📚 Key Learning Outcomes

- Decision Tree Regression
- Regression Model Training
- Model Prediction
- Model Evaluation
- Data Visualization
- End-to-End Machine Learning Workflow

---

## 👨‍💻 Author

**Phaneendra G**

GitHub: https://github.com/phaneendrag1

LinkedIn: https://www.linkedin.com/in/phaneendra-g/

---

⭐ If you found this project useful, consider giving it a **Star**!
