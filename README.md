# Pima Diabetes MLP
Deep learning project predicting diabetes outcomes from medical data using a multi-layer perceptron model. Includes both baseline and optimized network designs in Keras.

---

## Context:

Developed as a midterm project for the course **ADTA 5550: Deep Learning with Big Data** in Spring 2025.

---

## Dataset Overview:

This project uses the Pima Indians Diabetes Dataset sourced from the UCI Machine Learning Repository. It contains data on 768 women of Pima heritage, each represented by 8 numerical health features such as glucose level, BMI, and insulin levels. The target variable indicates whether a patient is diabetic (1) or non-diabetic (0). The dataset was loaded via CSV for preprocessing and analysis.

---

## Summary:

This project compares two multi-layer perceptron (MLP) architectures:

###  Part I: Baseline MLP
- Layers: 16 → 8 → 1
- Activation: ReLU (hidden), Sigmoid (output)
- Optimizer: Adam

###  Part II: Redesigned MLP
- Layers: 12 → 8 → 1
- Enhancements: Dropout (0.4), Batch Normalization
- Goal: Reduce overfitting and improve accuracy

---

## Tools & Libraries:
- Python 3
- Jupyter Notebook
- Keras / TensorFlow
- Pandas, NumPy, Scikit-learn, Matplotlib

---

## Repository Files

| File | Description |
|------|-------------|
| `Aman_PimaDiabetes-1.ipynb` | Baseline model implementation |
| `AG_RePimaDiabetes-1.ipynb` | Redesigned model with improvements |
| `ADTA5550_midterm.docx` | Written portion with metrics, discussion, and visuals |

---

## Objective :

To demonstrate practical skills in:
- Neural network modeling
- Data preprocessing and analysis
- Model evaluation and comparison
