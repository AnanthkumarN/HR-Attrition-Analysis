# HR Attrition Management

I have performed this Machine Learning project for analyzing employee attrition in an organization. The project focuses on identifying key factors contributing to employee turnover and leveraging machine learning models to predict attrition.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Setup Instructions](#setup-instructions)
4. [Features](#features)
5. [Data Description](#data-description)
6. [Usage](#usage)
7. [Acknowledgments](#acknowledgments)

---

## Project Overview

Employee attrition is a critical issue for organizations as it impacts productivity and costs. This project aims to:

- Analyze factors influencing employee attrition.
- Perform exploratory data analysis (EDA) to identify trends and insights.
- Build machine learning models to predict employee attrition.
- Suggest actionable insights to reduce turnover.

---

## Technologies Used

- **Python**: Programming language.
- **Jupyter Notebook**: For interactive data exploration and analysis.
- **Pandas**: Data manipulation and preprocessing.
- **NumPy**: Numerical computations.
- **Seaborn & Matplotlib**: Data visualization.
- **Scikit-learn**: Machine learning models and evaluation metrics.

---

## Setup Instructions

1. Clone this repository:

   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:

   ```bash
   cd HR-Attrition-Management
   ```

3. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the `HR Attrition Management.ipynb` file in Jupyter Notebook.

---

## Features

- **Data Preprocessing**:
  - Handling missing values and inconsistent data.
  - Encoding categorical variables.
  - Removing outliers using statistical techniques (e.g., IQR).
- **Exploratory Data Analysis (EDA)**:
  - Visualizing attrition trends by age, department, and other factors.
  - Generating histograms, box plots, and correlation heatmaps.
- **Machine Learning Models**:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - Gradient Boosting (e.g., XGBoost, if implemented)
- **Model Evaluation**:
  - Confusion Matrix
  - Accuracy, Precision, Recall, F1-Score
  - ROC Curve and AUC Score
- **Feature Importance Analysis**: Identifying key predictors of attrition.

---

## Data Description

The dataset includes the following columns (example):

- **EmployeeID**: Unique identifier for each employee.
- **Age**: Employee's age.
- **Department**: Department in which the employee works.
- **JobSatisfaction**: Satisfaction level of the employee with their job.
- **Attrition**: Target variable indicating whether the employee left the organization.

Additional columns represent demographic, performance, and satisfaction metrics.

---

## Usage

- Execute the notebook cell by cell to reproduce the analysis and results.
- Update the dataset path if required.
- Experiment with additional machine learning models or hyperparameter tuning.

---

## Acknowledgments

- **Dataset**: This project uses publicly available HR attrition datasets (e.g., Kaggle or similar sources).
- **Libraries**: Thanks to the open-source contributors of the Python libraries used in this project.

---

