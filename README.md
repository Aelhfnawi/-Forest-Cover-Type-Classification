# 🌲 Forest Cover Type Classification

This project focuses on predicting the type of forest cover based on cartographic and environmental features using the UCI Covertype dataset. The classification is a multi-class problem involving different types of forest cover (e.g., Spruce/Fir, Lodgepole Pine, etc.).

## 📁 Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/covertype)
- **Size**: 581,012 rows × 55 columns
- **Target**: `Cover_Type` (Multi-class with 7 forest cover categories)

## 🔧 Tools & Libraries
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost

## 🔍 Steps Followed
1. **Data Exploration**
   - Checked for nulls and data types
2. **Preprocessing**
   - Encoded categorical columns
   - Scaled features using `StandardScaler`
3. **Modeling**
   - `RandomForestClassifier`
   - `XGBoost Classifier`
4. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Feature Importance Visualization

## 📊 Results
- Models achieved high classification accuracy on the test set
- Feature importances highlight key environmental attributes for forest type

## 📌 Future Work
- Try deep learning models (e.g., TabNet or MLP)
- Hyperparameter tuning for XGBoost and RF
- Deployment via Streamlit or Flask

---

## 🤝 Acknowledgments
- UCI Machine Learning Repository
- Scikit-learn and XGBoost open-source contributors

## 🔗 Connect with Me
Feel free to reach out or explore more projects on my [GitHub](https://github.com/Aelhfnawi)
