# 🩺 Disease Prediction System using Machine Learning & Deep Learning

---

## 📌 Problem Statement
Predict possible diseases based on user-provided symptoms using Machine Learning and Deep Learning techniques.  
The system should also suggest precautionary measures, making it useful as a basic healthcare decision support tool.

---

## 📖 Overview
This project is a Disease Prediction System that:
- Takes symptoms as input
- Predicts top 3 possible diseases
- Shows prediction probabilities
- Suggests precautions for each disease

The goal is to combine prediction with actionable insights to simulate a real-world AI health assistant.

---

## 🎯 Objectives
- Build a multi-class disease classification model  
- Compare Machine Learning and Deep Learning approaches  
- Improve realism using data augmentation  
- Provide user-friendly and meaningful outputs  

---

## 🔗 Dataset Source
Dataset used in this project:  
https://github.com/anujdutt9/Disease-Prediction-from-Symptoms  

### Dataset Details:
- 400+ symptoms (binary encoded: 0/1)  
- Target column: prognosis (disease name)  
- Separate training and test datasets used  

---

## ⚙️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib  

---

## 🧠 Methodology

### 1. Data Preprocessing
- Loaded dataset using Pandas  
- Removed unnecessary columns  
- Converted categorical labels into numerical form using Label Encoding  

---

### 2. Data Augmentation
To simulate real-world conditions:
- Used random subsets of symptoms  
- Added noise (extra symptoms)  
- Simulated missing symptoms  

This improves model robustness and generalization.

---

### 3. Feature & Label Separation
- Features (X): Symptoms  
- Labels (y): Disease  

---

### 4. Model Training

#### 🔹 Logistic Regression (Baseline Model)
- Simple linear model  
- Used for comparison  

#### 🔹 ANN (Artificial Neural Network)
- Architecture: 128 → 64 → Output  
- Activation: ReLU  
- Output: Softmax  

#### 🔹 DNN (Deep Neural Network)
- Architecture: 256 → 128 → 64 → Output  
- Dropout used to reduce overfitting  

---

### 5. Model Evaluation
- Evaluated on separate test dataset  
- Accuracy used as primary metric  

---

### 6. Top-3 Prediction System
Instead of predicting a single disease, the system returns:
1. Most probable disease  
2. Second most probable disease  
3. Third most probable disease  

This makes predictions more realistic and useful.

---

### 7. Precaution Recommendation System
- A separate dataset maps diseases to precautions  
- System displays preventive measures for predicted diseases  

---

## 📊 Results

| Model | Accuracy |
|------|--------|
| Logistic Regression | ~XX% |
| ANN | 0.976 |
| DNN | 0.976 |

Note: High accuracy is due to structured dataset.

---

## 🔍 Sample Output

### Input Symptoms:
itching, skin_rash, fatigue  

### Output:
1. Fungal infection (56%)  
   - Keep area dry  
   - Use antifungal cream  
   - Avoid sharing items  

2. Drug Reaction (13%)  
   - Stop medication  
   - Consult doctor  
   - Avoid allergens  

3. Chicken pox (6%)  
   - Avoid scratching  
   - Maintain hygiene  
   - Stay isolated  

---

## 🎲 Additional Features
- Random symptom testing  
- Model comparison  
- Probability-based predictions  

---

## 🚀 How It Works
Symptoms → Model → Top 3 Predictions → Precautions  

---

## 📉 Limitations
- Dataset is highly structured and clean  
- Not real-world clinical data  
- May not generalize perfectly in real scenarios  

---

## 🔮 Future Scope
- Use real hospital datasets  
- Add disease severity prediction  
- Deploy using Streamlit web app  
- Integrate doctor recommendation system  

---

## ▶️ How to Run

Install dependencies:
pip install pandas numpy scikit-learn tensorflow matplotlib  

Run notebook:
jupyter notebook  

---

## 🎤 Viva Summary
This project applies machine learning and deep learning techniques to predict diseases from symptoms. It enhances realism using data augmentation and provides top-3 predictions along with precautionary recommendations, making it a practical healthcare support system.

---

## 👩‍💻 Author
Hemashi Yeole  

---

## ⭐ Conclusion
This project demonstrates how AI can assist healthcare systems by combining:
- Prediction  
- Probability ranking  
- Actionable medical guidance  
