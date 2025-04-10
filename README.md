# ❤️ Heart Disease Prediction using Machine Learning

This project uses machine learning classification algorithms to predict the presence of heart disease in a patient using health-related features. The goal is to help identify potential heart disease cases using automated analysis.

## 📁 Dataset

The dataset used in this project is `heart.csv`, which contains 14 health-related features collected from patient medical records.

### Features:

| Feature      | Description |
|--------------|-------------|
| `age`        | Age of the patient |
| `sex`        | Gender (1 = male, 0 = female) |
| `cp`         | Chest pain type (0–3) |
| `trestbps`   | Resting blood pressure |
| `chol`       | Serum cholesterol (mg/dl) |
| `fbs`        | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| `restecg`    | Resting ECG results (0–2) |
| `thalach`    | Max heart rate achieved |
| `exang`      | Exercise-induced angina (1 = yes; 0 = no) |
| `oldpeak`    | ST depression (exercise vs rest) |
| `slope`      | Slope of ST segment (0–2) |
| `ca`         | Number of major vessels (0–3) |
| `thal`       | Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect) |
| `target`     | Target variable (1 = disease, 0 = no disease) |

---

## 🧠 Algorithms Used

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## 📊 Visualizations

- Target class distribution
- Correlation heatmap
- Histograms of key features
- Feature importance from Random Forest
- Confusion matrix heatmap
- Accuracy comparison of classifiers

---

## ✅ Model Evaluation

Each model was evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

## 📌 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction
