# Breast Cancer Classification

A Neural Network project that predicts whether a breast cancer tumor is **malignant** or **benign** based on diagnostic features.  
The goal is to demonstrate data preprocessing, model building, training visualization, and evaluation using a deep learning approach.

---

## 📊 Dataset
- **Source:** `sklearn.datasets.load_breast_cancer`  
- **Features:** 30 numeric features, including:  
  `mean radius, mean texture, mean perimeter, mean area, mean smoothness, ...`  
- **Target:** `target` (Malignant = 0, Benign = 1)  

---

## 🚀 Project Objectives
1. Load and explore the dataset.  
2. Split data into training and testing sets.  
3. Scale features using `StandardScaler`.  
4. Build models:
   - **Model 1:** Logistic Regression  
   - **Model 2:** RandomeForestClassifier with GridSearchCV  
   - **Model 3:** Neural Network (tuned epochs, batch size, learning rate)  
5. Train the model and visualize training & validation metrics.  
6. Evaluate model performance with accuracy, classification report, and confusion matrix.  

---

## 🛠️ Models and Techniques Used

| Model       | Technique                    | Tools & Libraries       |
|------------|------------------------------|------------------------|
| Model 1     | Logistic Regression         | scikit-learn           |
| Model 2     | RandomeForestClassifier     | scikit-learn           |
| Model 3     | Neural Network              | TensorFlow / Keras     |

---

## ⚙️ Evaluation Metrics
- Accuracy Score    
- Confusion Matrix  
- Training & Validation Loss / Accuracy Plots using Matplotlib  

---

## ✅ Results Summary

| Model                       | Accuracy | Notes                     |
|------------------------------|----------|---------------------------|
| Model 1: Baseline model | ~97.37%    | Good initial performance  |
| Model 2: Improved model | ~96.5%     | Not as good as Baseline   |
| Model 3: Optimized model| ~98.25%    | Best performance achieved |
