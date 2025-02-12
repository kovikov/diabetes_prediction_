![image](https://github.com/user-attachments/assets/ebfbc296-07a9-4aab-a4a9-bae701fd2107)


# Diabetes Prediction Project

## 📌 Project Overview
This project focuses on predicting the likelihood of diabetes onset using machine learning techniques. The goal is to develop an accurate predictive model that can assist healthcare professionals in identifying at-risk patients early, allowing for timely preventive measures.

## 📊 Dataset Description
The dataset contains patient records with various features related to demographics, health conditions, and medical test results. The key attributes include:
- **Gender**: Male or Female
- **Age**: Patient's age
- **Hypertension**: 0 (No), 1 (Yes)
- **Heart Disease**: 0 (No), 1 (Yes)
- **Smoking History**: Categories (Never, Former, Current, etc.)
- **BMI**: Body Mass Index
- **HbA1c Level**: Blood sugar indicator
- **Blood Glucose Level**: Glucose concentration in blood
- **Diabetes (Target Variable)**: 0 (No Diabetes), 1 (Diabetic)

## 🚀 Machine Learning Models Used
Several machine learning models were implemented and evaluated to find the best-performing model for diabetes prediction:
- **Logistic Regression**
- **Random Forest Classifier**
- **Gradient Boosting (XGBoost, LightGBM, CatBoost)**
- **Support Vector Machine (SVM)**
- **Neural Networks (MLPClassifier)**
- **Stacking Classifier (Ensemble Approach)**
- **AutoML (TPOT for automatic model selection and tuning)**

## 📈 Key Findings & Recommendations
- **Gradient Boosting and Neural Networks performed the best**, achieving **97% accuracy** with the highest recall for diabetic patients.
- **Random Forest also showed strong performance** but was slightly less effective than Gradient Boosting.
- **SVM and Logistic Regression struggled with recall**, meaning they misclassified a higher number of diabetic patients.
- **Hyperparameter tuning improved performance**, optimizing Random Forest to reduce false negatives.
- **Recommendation:** Deploy Gradient Boosting or Neural Networks for real-world implementation, ensuring that recall remains high to minimize undiagnosed diabetes cases.

## ⚙️ Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model training script:
   ```bash
   python train_model.py
   ```
4. Predict on new data:
   ```bash
   python predict.py --input new_patient_data.csv
   ```

## 📊 Results & Performance Metrics
- **Accuracy**: ~97%
- **Precision (Diabetes Class)**: 97%
- **Recall (Diabetes Class)**: 69% (Best in Gradient Boosting & Neural Networks)
- **F1-score**: 81%
- **AUC-ROC**: 0.98 (Indicating high discriminatory power of the model)

## 🏥 Conclusion
This project successfully developed a high-performance diabetes prediction model. The insights gained can help healthcare professionals take **preventive actions** and improve patient outcomes. Future work may include integrating **real-time prediction pipelines** into healthcare systems.

## 🔗 References
- [Scikit-Learn Documentation](https://scikit-learn.org/)
- [XGBoost](https://xgboost.readthedocs.io/)
- [LightGBM](https://lightgbm.readthedocs.io/)
- [TPOT AutoML](https://epistasislab.github.io/tpot/)

---
👨‍💻 **Developed by:** *Your Name*
📍 **GitHub Repository:** [Your Repo Link]

# diabetes_prediction_
