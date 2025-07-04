# 💧 Water Potability Prediction System

A Machine Learning project that predicts whether water is safe to drink based on physicochemical features like pH, hardness, solids, sulfate, and more. This project leverages classification algorithms to build a predictive model and help ensure water quality analysis.

## 📌 Project Overview

Contaminated water can cause serious health issues. Using data science, we aim to classify water samples as **potable** or **non-potable** based on measurable characteristics. This project includes data cleaning, EDA, feature scaling, model training, evaluation, and improvement using techniques like SMOTE.

## 🚀 Technologies & Tools Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (SVM, Random Forest, XGBoost)  
- Imbalanced-learn (SMOTE)  

## 📂 Dataset

- Source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/water+quality)  
- Features: pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic Carbon, Trihalomethanes, Turbidity  
- Target: `Potability` (0 = Not Safe, 1 = Safe)

## 📈 Process Flow

1. **Data Loading & Cleaning**  
2. **Exploratory Data Analysis (EDA)**  
3. **Handling Missing Values**  
4. **Feature Scaling**  
5. **Model Training & Evaluation**  
6. **Balancing Data using SMOTE**  
7. **Accuracy & ROC-AUC Comparison**

## ✅ Models Used

| Model           | Accuracy | ROC-AUC |
|----------------|----------|---------|
| Random Forest   | ~69%     | ~0.65   |
| SVM             | ~67%     | ~0.62   |
| XGBoost         | ~68%     | ~0.64   |

## 🧪 Evaluation Metrics

- Accuracy  
- Confusion Matrix  
- ROC-AUC Score  
- Precision & Recall  

## 📊 Sample Output

- Feature Importance Visualization  
- Confusion Matrix Heatmaps  
- ROC Curves  

## 🤖 Future Enhancements

- Use of ensemble models and hyperparameter tuning  
- Deploy as a web app using Flask or Streamlit  
- Integration with real-time IoT sensor data  

## 🧠 Author

**Aditya Rawat**  
📫 [adityarawat.online@gmail.com](mailto:adityarawat.online@gmail.com)    
🔗 [LinkedIn](#) | [GitHub](#)

## 💡 License

This project is open source and available under the [MIT License](LICENSE).
