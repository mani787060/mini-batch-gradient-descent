# Mini-Batch Gradient Descent

## 📌 Project Overview

This project demonstrates the implementation of **Mini-Batch Gradient Descent (MBGD)**, a popular optimization algorithm that combines the advantages of both Batch Gradient Descent and Stochastic Gradient Descent.

Using a dataset generated with Scikit-Learn's `make_regression`, the notebook shows how model parameters are updated using small batches of data instead of the entire dataset or a single sample. This approach provides faster training while maintaining stable convergence.

---

## 🎯 Objectives

* Understand the working of Mini-Batch Gradient Descent
* Learn how batch creation and shuffling work
* Compare Batch, Stochastic, and Mini-Batch Gradient Descent
* Observe parameter updates and convergence behavior
* Study the impact of batch size on training performance

---

## 📂 Dataset

**Dataset Used:** `make_regression`

A synthetic regression dataset generated using Scikit-Learn to demonstrate optimization algorithms and parameter learning.

---

## 📖 Concepts Covered

* Linear Regression
* Mini-Batch Gradient Descent
* Batch Gradient Descent
* Stochastic Gradient Descent
* Mean Squared Error (MSE)
* Learning Rate
* Batch Creation
* Parameter Optimization
* Convergence

---

## 🛠️ Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## ⚙️ Implementation Steps

### Data Preparation

* Generate regression data using `make_regression`
* Visualize the dataset

### Batch Creation

* Shuffle the training data
* Divide data into smaller mini-batches
* Define batch size

### Gradient Computation

* Calculate predictions for each batch
* Compute gradients using mini-batch samples
* Calculate loss values

### Parameter Updates

* Update model parameters after each batch
* Repeat for multiple epochs until convergence

### Visualization

* Track loss reduction across epochs
* Visualize convergence behavior
* Compare optimization performance

---

## 🔍 Key Observations

* Mini-Batch Gradient Descent is faster than Batch Gradient Descent.
* It produces more stable updates than Stochastic Gradient Descent.
* Batch size affects both training speed and convergence quality.
* Proper batch sizes often lead to efficient and reliable optimization.

---

## ✅ Advantages

* Faster training on large datasets
* Better convergence than pure SGD
* Efficient memory utilization
* Widely used in Machine Learning and Deep Learning

---

## 💻 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## 🏁 Conclusion

Mini-Batch Gradient Descent is one of the most widely used optimization techniques in modern Machine Learning. By updating parameters using small batches of data, it achieves a good balance between computational efficiency and stable convergence, making it ideal for large-scale learning problems.


