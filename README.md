# 🚀 Linear Regression from Scratch

This project implements **Linear Regression from scratch using Python**, without relying on machine learning libraries for training.

The goal of this project is to understand how a model learns using **Gradient Descent** and how parameters are optimized step by step.

---

## 📌 Features

✔ Implemented hypothesis function (y = mx + b)  
✔ Mean Squared Error (MSE) loss function  
✔ Gradient Descent optimization  
✔ Parameter updates (slope & intercept)  
✔ Early Stopping for faster convergence  
✔ Evaluation metrics:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score  

✔ Visualizations:
- 📉 Loss vs Iterations  
- 📈 Best Fit Line  
- 🔵 Actual vs Predicted  

✔ Comparison with Scikit-learn  

---

## 📊 Dataset

A simple dataset is used to clearly understand the working:

X = [1, 2, 3, 4, 5]
Y = [5, 7, 9, 11, 13]

This follows the equation:


y = 2x + 3


---

## ⚙️ How It Works

1. Initialize parameters (m, b)
2. Predict values using:

y = mx + b

3. Compute error using MSE
4. Calculate gradients
5. Update parameters using Gradient Descent
6. Repeat until convergence

---

## 📈 Results

- Model learns:
- Slope (m) ≈ 2  
- Intercept (b) ≈ 3  

- Loss decreases smoothly over iterations  
- Predictions closely match actual values  

---

## 📊 Visual Output

### 🔹 Loss vs Iterations
Shows how the model minimizes error over time.

### 🔹 Best Fit Line
Displays regression line fitting the data points.

### 🔹 Actual vs Predicted
Compares real values with model predictions.

---

## 🤖 Sklearn Comparison

The results are validated using `sklearn.linear_model.LinearRegression`:

- Matching slope and intercept  
- Confirms correctness of implementation  

---

## 🧠 Learning Outcomes

Through this project, I understood:

- How Gradient Descent works internally  
- How models update parameters  
- Importance of loss minimization  
- Difference between prediction and optimization  
- How to evaluate model performance  

---

## 🚀 Future Improvements

- Multiple Linear Regression  
- Regularization (L1 & L2)  
- Real-world datasets  
- Model deployment using Flask  

---

## 💻 Tech Stack

- Python  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📌 Author

**Vidhi Sharma**  
BTech AIML Student  

---

## ⭐ If you found this useful

Give it a ⭐ on GitHub and feel free to connect!
