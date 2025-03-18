# Salary-vs-Experience-Linear-Regression
# Linear Regression: Experience vs. Salary Prediction

## Overview
This project demonstrates a simple **Linear Regression** model using Python to predict an employee's salary based on years of experience. It utilizes the **scikit-learn** library for training the model and **matplotlib** for visualizing the results.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Dataset
The dataset consists of the following example data:

| Years of Experience (X) | Salary (LPA) (Y) |
|-------------------------|------------------|
| 1                       | 3                |
| 3                       | 6                |
| 5                       | 9                |
| 7                       | 12               |
| 10                      | 18               |

## Installation
To run this project, ensure you have Python installed along with the required libraries. You can install dependencies using:
```bash
pip install numpy pandas matplotlib scikit-learn
```

## Code Explanation
1. **Import Required Libraries**
   - NumPy & Pandas for data handling
   - Matplotlib for visualization
   - Scikit-learn for model training

2. **Define Data**
   - `experience` (independent variable) and `salary` (dependent variable)
   - Reshape `experience` for model training

3. **Train the Linear Regression Model**
   - Fit the model using the given experience and salary values

4. **Make Predictions**
   - Predict salary for 6 years of experience

5. **Visualization**
   - Scatter plot of actual salaries
   - Regression line indicating the model’s predictions

## Usage
Run the script using:
```bash
python script.py
```
It will output the predicted salary and display the **Experience vs. Salary** graph.

## Output Example
```bash
Predicted salary for 6 years of experience: 10.5 LPA
```
And a graph will be displayed with actual salaries and the regression line.

## Author
DivyaRekha

