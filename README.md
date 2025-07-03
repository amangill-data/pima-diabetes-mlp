# pima-diabetes-mlp
Deep learning project predicting diabetes outcomes from medical data using a multi-layer perceptron model. Includes both baseline and optimized network designs in Keras.

---

## Context:

Developed as a midterm project for the course **ADTA 5550: Deep Learning with Big Data** in Spring 2025.

---

## Dataset Overview:

- **Dataset:** Pima Indians Diabetes Dataset (UCI Repository)
- **Samples:** 768 women (Pima heritage)
- **Features:** 8 numeric health metrics (e.g., glucose level, BMI, insulin)
- **Target:** 1 = diabetic, 0 = non-diabetic

---

## Summary:

This project compares two multi-layer perceptron (MLP) architectures:

###  Part II: Baseline MLP
- Layers: 16 → 8 → 1
- Activation: ReLU (hidden), Sigmoid (output)
- Optimizer: Adam

###  Part III: Redesigned MLP
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
