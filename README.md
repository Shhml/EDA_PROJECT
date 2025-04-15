# 💎 Diamond Price Prediction - Exploratory Data Analysis

This project focuses on performing **Exploratory Data Analysis (EDA)** on the largest available diamond dataset. The goal is to uncover key patterns and factors that influence diamond prices, such as carat, cut, color, clarity, and other physical attributes.

---

## 📌 Project Objective

- Understand the structure and quality of the diamond dataset
- Identify key features that affect diamond pricing
- Visualize relationships between features using graphs and plots
- Generate actionable insights for further modeling or business strategy

---

## 📊 Dataset Information

- **Source**: [Kaggle - Diamonds Dataset](https://www.kaggle.com/datasets/shivam2503/diamonds)
- **Total Rows**: 53940
- **Features**: `carat`, `cut`, `color`, `clarity`, `depth`, `table`, `price`, `x`, `y`, `z`

---

## 📈 Key Insights from EDA

- **Carat and Price** have a strong positive correlation — heavier diamonds are generally more expensive.
- **Cut, Clarity, and Color** also influence price but with varying intensity.
- Diamonds with **Ideal cut** and **high clarity (IF, VVS1)** tend to have higher prices.
- The price distribution is **right-skewed**, meaning most diamonds are relatively affordable, while a few are extremely expensive.
- Detected some **outliers** in dimensions (`x`, `y`, `z`) and price that may need cleaning before modeling.

---

## 🧰 Tools & Technologies Used

- **Python**
- **Pandas** & **NumPy** – for data manipulation
- **Matplotlib** & **Seaborn** – for visualization
- **Jupyter Notebook** – for analysis
