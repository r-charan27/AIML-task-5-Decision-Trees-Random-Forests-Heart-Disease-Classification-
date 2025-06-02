# AIML-task-5-Decision-Trees-Random-Forests-Heart-Disease-Classification-
# 🌳 Decision Trees & Random Forests – Heart Disease Classification

## 📌 Objective
This project is part of **Task 5** of the AI & ML Internship. The goal is to understand and apply **tree-based models** — specifically **Decision Trees** and **Random Forests** — for classification. We'll also visualize the tree, examine overfitting, evaluate model accuracy, and interpret feature importance.

---

## 📁 Dataset
- **Dataset Used**: ["C:/Users/RAMCHARAN/Downloads/heart.csv"]

This dataset includes patient health metrics to predict heart disease.

---

## 🛠 Tools & Libraries
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🔍 Steps Performed

### 1. Load & Preprocess Data
- Loaded heart disease dataset
- Split into features (`X`) and labels (`y`)

### 2. Train/Test Split
- Used `train_test_split()` from `sklearn`

### 3. Decision Tree Classifier
- Trained a full tree
- Visualized using `plot_tree()`
- Evaluated with confusion matrix and classification report

### 4. Controlled Overfitting
- Re-trained a **pruned tree** with `max_depth=4`
- Compared accuracy and generalization

### 5. Random Forest Classifier
- Trained with 100 trees
- Compared accuracy with Decision Tree
- Extracted and visualized **feature importances**

### 6. Cross-Validation
- Used 5-fold cross-validation to get average accuracy for both models

---

## 📈 Results

| Model                    | Accuracy | Cross-Validation Accuracy |
|--------------------------|----------|----------------------------|
| Decision Tree            | ~80%     | ~79%                       |
| Pruned Decision Tree     | ~83%     | ~82%                       |
| Random Forest            | ~87%     | ~85%                       |

---

## 📊 Visualizations
- 📉 Decision Tree visualization using `plot_tree()`
- 📌 Feature importance plot from Random Forest

---
Submitted by:MUMMADI RAMCHARAN
