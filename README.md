
# 🏡 Week 5: House Price Prediction – Feature Engineering & Modeling

This project is part of **Week 5** of the **Celebal Summer Internship** program.

The assignment involved building a robust regression pipeline to **predict house prices** using the **House Prices - Advanced Regression Techniques** dataset from Kaggle. The goal was to perform **data preprocessing, feature engineering, feature selection**, and build multiple machine learning models for comparison and final prediction.

---

## 📌 Features

- ✅ Comprehensive Data Preprocessing:
  - Null value handling
  - Feature construction (`TotalSF`, square footage, etc.)
  - One-hot encoding of categorical features
  - Log transformation for skewed target

- 🧠 Predictive Modeling (Regression):
  - Simple Linear Regression
  - Multiple Linear Regression
  - Polynomial Regression (Degree 2)
  - Ridge, Lasso, ElasticNet Regression
  - Decision Tree Regressor
  - Random Forest Regressor (with Grid Search)
  - Support Vector Regressor (with scaling)
  - K-Nearest Neighbors Regressor

- 🔍 Feature Engineering & Selection:
  - `SelectKBest` for top features
  - PCA for dimensionality reduction (50 components)
  - t-SNE for 2D visualization of price clusters

- 📈 Model Evaluation:
  - RMSE, R², MSE for model comparison
  - Final model selection via `GridSearchCV`

---

## 📂 File Structure

```
Celebal-Week5/
├── week5.ipynb                # Main Jupyter Notebook
├── train.csv                 # Training data from Kaggle
├── test.csv                  # Test data from Kaggle
├── submission.csv            # Final submission predictions
├── requirements.txt          # Python dependencies
└── README.md                 # This file
```

---

## 🚀 How to Run

### 1. Clone this Repository

```bash
git clone https://github.com/jagrutidesale04/Celebal-Week5.git
cd Celebal-Week5
```

### 2. (Optional) Create a Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate      # Windows
# or
source venv/bin/activate     # macOS/Linux
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

```bash
jupyter notebook week5.ipynb
```

---

## 📉 Visualizations Included

- Correlation heatmap
- PCA projections
- t-SNE clustering
- Bar plot of RMSE scores
- Final prediction comparison

---

## 📎 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
scipy
```

---

## 👩‍💻 Author

**Jagruti Desale**  
B.Tech – Data Science and Engineering (3rd Year)  
Summer Intern @ Celebal Technologies

🔗 [GitHub](https://github.com/jagrutidesale04)  
💼 [LinkedIn](https://www.linkedin.com/in/jagruti-desale-jd04)

---

## 📜 License

This project is intended for academic and learning purposes only as part of the Celebal Summer Internship program.
