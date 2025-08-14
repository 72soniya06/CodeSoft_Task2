# CodeSoft_Task2
# 🌸 Iris Flower Species Prediction

This project predicts the species of an Iris flower based on its sepal and petal measurements using a machine learning model.  
It uses the classic [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris), one of the most popular datasets for classification tasks.

---

## 📌 Project Overview

The Iris dataset contains 150 samples of iris flowers, divided evenly into three species:

- **Iris setosa**
- **Iris versicolor**
- **Iris virginica**

Each sample contains the following measurements (in centimeters):

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The goal of this project is to train a machine learning model that predicts the species of an iris flower based on these four features.

---

## 📂 Dataset Description

| Feature         | Description |
|-----------------|-------------|
| SepalLengthCm   | Length of the sepal in centimeters |
| SepalWidthCm    | Width of the sepal in centimeters |
| PetalLengthCm   | Length of the petal in centimeters |
| PetalWidthCm    | Width of the petal in centimeters |
| Species         | Iris species (Setosa, Versicolor, Virginica) |

---

## ⚙️ Installation & Requirements

Make sure you have Python 3.7+ installed.

Install dependencies:

```bash
pip install pandas numpy scikit-learn gradio
