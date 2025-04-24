# heartdiseaseprediction


# ❤️ Heart Disease Risk Prediction using Machine Learning  
**Course:** DATA 2206 — Capstone Project  
**Team:** Data Wizards  
**Instructor:** Sam Plati  
**Submitted On:** May 4, 2024  

## 🧑‍🤝‍🧑 Team Members
- Akshay Kuttickattu Binu (100729165)  
- Blesson Issac (100935589)  
- Dils Siby (100886198)  
- Immanuel Sebastian (100935313)  
- Tarun Sabu (100913516)  
- Varsha Reghu (100930107)  

---

## 📘 Project Summary

Heart disease is one of the leading causes of death globally. Early prediction plays a crucial role in preventing complications and reducing mortality. Our project utilizes **machine learning** models trained on clinical and demographic data to predict the presence or absence of heart disease.

The project includes **data preprocessing**, **exploratory data analysis**, **feature engineering**, and the implementation of multiple models including **SVM**, **Random Forest**, and **Logistic Regression**. The best-performing model is evaluated based on **recall**, which is critical for medical applications where false negatives are risky.

---

## 🗂️ Dataset Description

- **Source:** Multispecialty hospital in India
- **Records:** 1000 patients  
- **Features:** 13 (e.g., age, gender, chest pain type, cholesterol, heart rate, etc.)  
- **Target Variable:** `target` (1 = has heart disease, 0 = healthy)

---

## ⚙️ Models Used

| Model              | Accuracy | Recall |
|-------------------|----------|--------|
| Support Vector Machine (SVM) | 98%      | **Best**
| Random Forest      | 97%      | High
| Logistic Regression| 96%      | Moderate

All models were evaluated on an 80:20 train-test split and optimized using grid search and cross-validation.

---

## 🔍 Key Features

- 📊 EDA using boxplots, histograms, pair plots
- 🧼 Data cleaning, encoding, SMOTE balancing
- 🧠 Model comparison and performance evaluation
- 📈 Classification metrics: precision, recall, F1-score, accuracy
- 🧪 Final insights and recommendations for model deployment in clinical decision-making

---

## 💡 Business Impact

- **Clinical Use**: Aid healthcare professionals with early risk screening
- **Policy Support**: Data-driven decisions for preventive programs
- **Scalable**: Can be extended to other diseases or regions

---

## 📁 Project Structure

```
HeartDiseasePredictor/
├── DataWizards_finalCode.html         # Model building and analysis notebook
├── Data Analytics Report_Data_Wizards.docx   # Final written report
├── Cardiovascular_Disease_Dataset.csv # Patient dataset (referenced in code)
├── README.md                          # Project documentation (this file)
```

---

## 🧠 Conclusion

- The **SVM model** delivered the best accuracy and recall, making it suitable for real-world health prediction.
- Our analysis highlights the importance of feature preprocessing and class balancing.
- The models show promise for use in diagnostic tools, and future improvements could include real-time integration or cloud-based apps.

---

## ⚠️ Limitations

- Imbalanced dataset (mitigated using SMOTE)
- Some models are less interpretable (e.g., Random Forest)
- High computational complexity during tuning

---

## 📝 Recommendations

- ✅ Use **recall-focused** evaluation in health AI systems
- ✅ Integrate with hospital systems for risk alerts
- ✅ Visualize decisions using SHAP or similar tools for transparency

---

## 📃 License

For educational and non-commercial use only.

