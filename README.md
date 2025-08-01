# Wine Quality Predictor 🍷

This project uses machine learning to predict the quality of wine based on various physicochemical features such as acidity, sugar content, pH, and alcohol percentage. It is implemented using Python and scikit-learn.

##  Dataset
The dataset used is the [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) from the UCI Machine Learning Repository. It includes red and white wine samples with quality ratings from 0 to 10.

##  Features
- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  
- Quality (Target)

##  ML Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  
- Accuracy metrics used: `accuracy_score`, `confusion_matrix`, and `classification_report`

##  Visualizations
- Heatmap of feature correlations  
- Quality distribution plot  
- Feature importance (for Random Forest)

##  Results
The Random Forest model achieved the highest accuracy among tested models. The most influential features for wine quality prediction were **alcohol**, **volatile acidity**, and **sulphates**.

##  Requirements
- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

Install them using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
