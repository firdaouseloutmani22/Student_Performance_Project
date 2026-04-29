# 🎓 A Hybrid Autoencoder–Deep Residual Network for Student Academic Outcome Prediction in Online Learning Environments

This project presents a hybrid deep learning approach for predicting student academic outcomes in online learning environments.

---

## 🚀 Overview

The increasing availability of educational data from digital learning platforms offers new opportunities for predicting student performance. However, traditional machine learning approaches often struggle with high-dimensional data and limited predictive capability for early risk detection.

To address these challenges, this project proposes a **hybrid model combining a Deep Autoencoder and a Deep Residual Network (DeepResNet)**.

---

## 🧠 Proposed Approach

The model consists of:

- 🔹 **Autoencoder** for unsupervised feature learning and dimensionality reduction  
- 🔹 **DeepResNet** for multi-class classification of student outcomes  

### ✔ Key advantages:
- Reduces data dimensionality  
- Handles sparsity  
- Captures complex nonlinear relationships  
- Improves prediction performance  

---

## 📊 Results

The proposed model achieves:

- **Accuracy:** 98.88%  
- **Precision:** 98.92%  
- **Recall:** 98.88%  
- **F1-score:** 98.88%  

### 📈 Comparison with baseline models:
The model significantly outperforms:
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  
- Decision Tree  
- K-Nearest Neighbors (KNN)  

---

## 📂 Project Structure
```
├── notebooks/
│ ├── Student_Performance_Prediction_Pipeline.ipynb
│ └── Baseline_Models_Student_Performance.ipynb
├── data/
│ └── baseline_features.npz
├── saved_model/
├── figures/
├── README.md
```

---

## 📊 Dataset

This project uses the **OULAD dataset (Open University Learning Analytics Dataset)**:

🔗 https://www.kaggle.com/datasets/anlgrbz/student-demographics-online-education-dataoulad

⚠️ The dataset is not included in this repository.  
Please download it from Kaggle and place it in the `data/` folder.

---

## 📂 Data Description

- `baseline_features.npz`: preprocessed feature matrix used for baseline machine learning models  
  (contains input features `X` and labels `y`)


