# AI & ML Internship Task 8

## Title
Simple & Multiple Linear Regression

---

## Objective

The objective of this task is to understand and implement Linear Regression for predictive modeling.

This task focuses on:
- Simple Linear Regression
- Multiple Linear Regression
- Train-Test Split
- Prediction
- Model Evaluation
- Regression Visualization

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

---

## Dataset Used

### Advertising Dataset

The dataset contains advertising expenditure across different media platforms and corresponding sales.

### Features

- TV Advertising Budget
- Radio Advertising Budget
- Newspaper Advertising Budget

### Target Variable

- Sales

Dataset File:

```text
advertising(1).csv
```

---

## Libraries Used

### Pandas
Used for:
- Loading dataset
- Data analysis
- Data preprocessing

### NumPy
Used for numerical operations.

### Matplotlib
Used for:
- Scatter plots
- Regression line visualization

### Seaborn
Used for enhanced data visualization.

### Scikit-learn
Used for:
- Train-Test Split
- Linear Regression
- Model Evaluation

---

## Tasks Performed

### 1. Loaded Dataset

Loaded Advertising dataset using Pandas.

```python
df = pd.read_csv('advertising(1).csv')
```

---

### 2. Explored Dataset

Used:

```python
df.head()
df.info()
df.describe()
```

to understand:

- Dataset structure
- Data types
- Statistical summary

---

## Simple Linear Regression

### Feature

```text
TV
```

### Target

```text
Sales
```

Goal:

Predict sales using TV advertising budget only.

---

### Train-Test Split

Used:

```python
train_test_split()
```

Training Data:

```text
80%
```

Testing Data:

```text
20%
```

---

### Model Training

Used:

```python
LinearRegression()
```

to train a Simple Linear Regression model.

---

### Prediction

Used:

```python
model.predict()
```

to predict sales values on unseen data.

---

### Regression Line Visualization

Visualized:

- Actual Data Points
- Regression Line

Purpose:
- Understand relationship between TV advertising and sales.

---

## Multiple Linear Regression

### Features

```text
TV
Radio
Newspaper
```

### Target

```text
Sales
```

Goal:

Predict sales using multiple advertising channels simultaneously.

---

### Model Training

Used:

```python
LinearRegression()
```

to train a Multiple Linear Regression model.

---

### Prediction

Generated sales predictions using:

```python
predict()
```

---

## Model Evaluation

### Mean Squared Error (MSE)

Used:

```python
mean_squared_error()
```

Purpose:

Measures average squared prediction error.

Lower MSE indicates better model performance.

---

### R-Squared Score (R²)

Used:

```python
r2_score()
```

Purpose:

Measures how well independent variables explain the target variable.

Range:

```text
0 to 1
```

Higher value indicates better model fit.

---

## Concepts Learned

### Simple Linear Regression

Uses one independent variable to predict one dependent variable.

Example:

```text
TV → Sales
```

---

### Multiple Linear Regression

Uses multiple independent variables to predict one dependent variable.

Example:

```text
TV + Radio + Newspaper → Sales
```

---

### Train-Test Split

Divides data into:

- Training Dataset
- Testing Dataset

Purpose:
- Prevent overfitting
- Evaluate model fairly

---

### Mean Squared Error (MSE)

Measures prediction error.

Lower value indicates better performance.

---

### R-Squared (R²)

Measures goodness of fit.

Higher value indicates stronger predictive capability.

---

## Key Observations

1. TV advertising expenditure shows a positive relationship with sales.

2. The regression line successfully captures the overall trend in the data.

3. Multiple Linear Regression performs better than Simple Linear Regression because it uses more information.

4. MSE helps measure prediction error quantitatively.

5. R² Score indicates how much variation in sales is explained by advertising expenditure.

---

## Outcome

Successfully implemented:

- Simple Linear Regression
- Multiple Linear Regression

The models were trained, evaluated, and visualized using the Advertising Dataset.

Model performance was assessed using:

- Mean Squared Error (MSE)
- R-Squared Score (R²)

This task provided practical understanding of predictive modeling and regression analysis.

---

## Files Included

```text
Linear_Regression_Advertising.ipynb
advertising(1).csv
README.md
```

---

## Repository Name

```text
AI-ML-Internship-Task-8
```

---

## Author

**Arya Chighare**  
Artificial Intelligence & Data Science  
YCCE, Nagpur
