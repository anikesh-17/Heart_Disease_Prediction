# Heart Disease Prediction Using Machine Learning

This project uses **Logistic Regression** to predict the presence of heart disease based on medical features.

## 🚀 Project Overview
The model analyzes clinical attributes such as:
- Age, Sex
- Chest Pain Type (cp)
- Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG (restecg)
- Maximum Heart Rate (thalach)
- Exercise-Induced Angina (exang)
- ST Depression (oldpeak)
- Slope, CA, Thal

Target Values:
- **1** → Heart disease present  
- **0** → No heart disease

## 🛠 Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-Learn  
- Logistic Regression  
- Google Colab / Jupyter Notebook

## 📊 Model Accuracy
- Training Accuracy: ~85%
- Test Accuracy: ~82%

## 🧪 Example Prediction
```python
input_data = (63,1,0,130,330,1,0,132,1,1.8,2,3,3)
prediction = model.predict([input_data])
```

## 📁 Dataset
File: **heart_disease_data.csv**  
Rows: 303  
Columns: 14  

## 📌 How to Run
1. Install dependencies  
```bash
pip install numpy pandas scikit-learn
```
2. Run the notebook or Python script  
3. Train the model  
4. Use the input section to test predictions  

---

Developed by **Anikesh Sharma**
