# ❤ Heart Disease Detection Using ANN  

##  Project Overview  
This project predicts the presence of **heart disease** in patients using an **Artificial Neural Network (ANN)**. The dataset contains medical attributes that help classify whether a person has heart disease (**target = 1**) or not (**target = 0**).  

---

## Technologies Used  
- **Python** 
- **TensorFlow/Keras** (For building the ANN model)  
- **Scikit-Learn** (For preprocessing and model evaluation)  
- **Pandas & NumPy** (For data manipulation)  
- **Matplotlib & Seaborn** (For data visualization)  
- **Flask/Streamlit** (For web deployment - optional)  

---

##  Dataset Description  
The dataset contains **14 medical attributes** used for prediction.  

| Feature Name  | Description |
|--------------|------------|
| **age**      | Age of the patient (years) |
| **sex**      | Gender (1 = Male, 0 = Female) |
| **cp**       | Chest pain type (0-3) |
| **trestbps** | Resting blood pressure (mm Hg) |
| **chol**     | Serum cholesterol (mg/dL) |
| **fbs**      | Fasting blood sugar > 120 mg/dL (1 = True, 0 = False) |
| **restecg**  | Resting ECG results (0-2) |
| **thalach**  | Maximum heart rate achieved |
| **exang**    | Exercise-induced angina (1 = Yes, 0 = No) |
| **oldpeak**  | ST depression induced by exercise |
| **slope**    | Slope of peak exercise ST segment (0-2) |
| **ca**       | Number of major vessels (0-3) colored by fluoroscopy |
| **thal**     | Thalassemia (1 = Normal, 2 = Fixed Defect, 3 = Reversible Defect) |
| **target**   | Heart Disease (1 = Present, 0 = Absent) |

---

##  How to Run the Project  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/bhargavianjaneya1/Heart-Disease-Detection-ANN.git
cd Heart-Disease-Detection-ANN
pip install -r requirements.txt
python heart_disease_ann.py
