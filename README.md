# 📊 Sentiment Analysis on Amazon Alexa Reviews
*CodeAlpha Internship – Data Analytics Task 4*

This project builds a machine learning model to classify Amazon Alexa customer reviews as **positive** or **negative** using Natural Language Processing (NLP).  
The aim is to understand customer sentiment, identify key trends, and help make data-driven product decisions.

---

## 🧪 **Workflow**

### 1️⃣ Data Cleaning & Preprocessing
- Converted text to lowercase
- Removed stopwords and punctuation
- Applied stemming (PorterStemmer)

### 2️⃣ Feature Extraction
- Used **CountVectorizer** to transform text into numerical vectors

### 3️⃣ Exploratory Data Analysis (EDA)
- Checked class balance
- Created word clouds
- Visualized review length distributions

### 4️⃣ Modelling
- Built Decision Tree, Random Forest, and XGBoost models
- Used train-test split (80%-20%)
- Performed hyperparameter tuning with GridSearchCV and cross-validation

### 5️⃣ Evaluation
- Accuracy score
- Confusion matrix
- Cross-validation scores

---

## ✨ **Results & Insights**
- Majority of reviews are *positive*
- Positive reviews often include words like “love”, “great”, “easy”
- Negative reviews include words like “bad”, “problem”, “poor”
- **XGBoost** achieved the best accuracy among tested models

---

## 📊 **Visualizations**
- Word clouds for positive and negative reviews
- Bar plots showing sentiment distribution
- Confusion matrix heatmap

---

## 📦 **Deliverables**
- Complete and well-documented notebook: `Data Exploration & Modelling.ipynb`
- Saved trained models (`.pkl` files)
- Predictions CSVs
- Visualizations
- `requirements.txt`
- `README.md` (this file)

✨ Thank you for exploring this project!
Feel free to fork ⭐, share feedback, and connect with me on LinkedIn
