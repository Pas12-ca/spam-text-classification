# Spam Text Classification (NLP)

## 📌 Project Overview
This project implements a professional NLP pipeline for **spam detection** using classical machine learning models and TF-IDF vectorization.

The objective is to classify SMS messages as **Spam** or **Non-Spam**, while handling class imbalance and evaluating models using cross-validation.

---

## 🧠 Models Used
- Logistic Regression (class_weight = balanced)
- Linear Support Vector Machine (SVM)
- Multinomial Naive Bayes

---

## ⚙️ NLP Pipeline
- Text preprocessing
- TF-IDF vectorization
- Unified sklearn Pipelines
- Cross-validation (F1-weighted)
- Test evaluation
- Error analysis

---

## 📊 Results

| Model               | CV F1-weighted | Test Accuracy | Test F1-weighted |
|--------------------|---------------|---------------|------------------|
| Logistic Regression | ~0.97         | ~0.97         | ~0.97           |
| Linear SVM          | ~0.97         | ~0.97         | ~0.97           |
| Naive Bayes         | ~0.95         | ~0.93         | ~0.92           |

✅ **Final model selected: Logistic Regression**  
Chosen for its strong performance, stability, and interpretability.

---

## 📈 Visualization
Model comparison is visualized using cross-validation F1-weighted scores.

---

## 🛠️ Technologies
- Python
- Scikit-learn
- Pandas / NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Repository Structure

---

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt

   jupyter notebook spam-text-classification.ipynb


## Author
- GitHub: Pas12-ca


