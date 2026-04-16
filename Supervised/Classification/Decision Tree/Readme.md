# 🌳 Decision Tree (Supervised Learning)

This project demonstrates the implementation of the **Decision Tree algorithm**, a widely used method in **Supervised Machine Learning** for solving classification problems.

---

## 📁 Project Structure

```id="9w3e0v"
Machine-Learning/
└── Supervised/
    └── Classification/
        └── Decision_Tree/
            ├── Decision_Tree.ipynb
            ├── car_data.csv
            └── README.md
```

---

## 🚀 Overview

A Decision Tree is a tree-based model that splits data into smaller subsets based on feature values.
It builds a flowchart-like structure where each internal node represents a decision, and each leaf node represents an output class.

---

## 🧠 Algorithm Intuition

* The dataset is split recursively based on feature values
* Splitting criteria include:

  * **Gini Index**
  * **Entropy (Information Gain)**
* The goal is to create nodes that are as pure as possible

---

## 📊 Dataset

* File: `car_data.csv`
* Date =`https://www.kaggle.com/datasets/gabrielsantello/cars-purchase-decision-dataset`
* Contains features related to car evaluation
* Used for training and testing the model

> You can replace this dataset with any classification dataset.

---

## ⚙️ Requirements

Install dependencies:

```bash id="sn9o6s"
pip install -r requirements.txt
```

Or manually:

```bash id="6o7j1y"
pip install numpy pandas matplotlib scikit-learn plotly
```

---

## ▶️ How to Run

1. Clone the repository:

```bash id="h1w3bm"
git clone https://github.com/lakshyasahu111/Machine-Learning.git
cd Machine-Learning
```

2. Navigate to the project folder:

```bash id="bz7vhu"
cd Supervised/Classification/Decision_Tree
```

3. Launch Jupyter Notebook:

```bash id="m2sl4m"
jupyter notebook
```

4. Open:

```id="0t8d77"
Decision_Tree.ipynb
```

---

## 📈 Output

* Model training and evaluation
* Prediction results on test data
* Visualization of decision-making process (if implemented)

---

## 📌 Features

* Clean and structured implementation
* Beginner-friendly notebook
* Supports visualization
* Easy to extend with more datasets

---

## 🔥 Future Improvements

* Implement pruning techniques
* Add hyperparameter tuning
* Compare with Random Forest
* Improve visualization using Graphviz

## ⭐ Contribute

Feel free to fork this repository and enhance the implementation!

---
