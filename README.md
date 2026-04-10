# 🩺 Disease Prediction System using ML & Deep Learning

## 📌 Overview
This project is a Disease Prediction System that predicts possible diseases based on given symptoms.  
It uses Machine Learning and Deep Learning models to provide:
- Top 3 disease predictions
- Prediction confidence (probability)
- Precaution suggestions for each disease

---

## 🎯 Objectives
- Predict diseases from symptoms
- Compare ML and DL models
- Provide realistic healthcare assistance
- Improve model robustness using data augmentation

---

## 📂 Dataset
- Training Dataset: training_data.csv  
- Test Dataset: test_data.csv  
- Precaution Dataset: precautions.csv  

### Features:
- 400+ symptoms (binary: 0 or 1)
- Target column: prognosis (disease name)

---

## ⚙️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib  

---

## 🧠 Models Used

### 1. Logistic Regression (Baseline Model)
- Simple machine learning model
- Used for comparison

### 2. ANN (Artificial Neural Network)
- Layers: 128 → 64
- Activation: ReLU
- Output: Softmax

### 3. DNN (Deep Neural Network)
- Layers: 256 → 128 → 64
- Dropout used to prevent overfitting

---

## 🔄 Data Augmentation
To make the dataset more realistic:
- Random subset of symptoms used
- Noise added (extra symptoms)
- Missing symptoms simulated

---

## 📊 Results

| Model | Accuracy |
|------|--------|
| Logistic Regression | ~XX% |
| ANN | 0.976 |
| DNN | 0.976 |

Note: Accuracy is high due to structured dataset.

---

## 🔍 Key Features

### ✅ Top-3 Prediction System
Instead of predicting only one disease:
1. Fungal infection (56%)
2. Drug Reaction (13%)
3. Chicken pox (6%)

---

### 💊 Precaution Recommendation
Each predicted disease includes:
- Preventive measures
- Basic healthcare suggestions

---

### 🎲 Random Testing
- Generates random symptom combinations
- Tests model generalization ability

---

## 🚀 How It Works
User Symptoms → Model → Top 3 Predictions → Precautions

---

## 📉 Limitations
- Dataset is highly structured
- Not real-world clinical data
- Accuracy may drop in real scenarios

---

## 🔮 Future Improvements
- Use real hospital datasets
- Add severity prediction
- Build a Streamlit web app
- Integrate doctor recommendation system

---

## ▶️ How to Run

Install dependencies:
pip install pandas numpy scikit-learn tensorflow matplotlib

Run the notebook:
jupyter notebook

---

## 🎤 Viva Explanation (Short)
This project uses machine learning and deep learning models to predict diseases from symptoms. It enhances realism using data augmentation and provides top-3 predictions along with precautions, making it a practical healthcare support system.

---

## 👩‍💻 Author
Hemashi Yeole
---

## ⭐ Conclusion
This project demonstrates how AI can assist in healthcare by combining:
- Prediction
- Probability ranking
- Actionable insights
