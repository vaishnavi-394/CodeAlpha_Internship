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





# 📊 Exploratory Data Analysis (EDA) on Swiggy Dataset  
*CodeAlpha Internship – Data Analytics Task 2*

This project performs detailed Exploratory Data Analysis on a real-world **Swiggy restaurant dataset**.  
The goal is to discover hidden patterns, perform hypothesis testing, and draw meaningful business insights using Python, Pandas, Seaborn, and statistical techniques.

---

## ✅ Project Objective
- Clean and explore restaurant data from Swiggy
- Perform statistical analysis on variables like ratings, price, cuisine, veg/non-veg, etc.
- Visualize key distributions and relationships
- Test hypotheses using t-tests and chi-square tests
- Derive useful insights for business decision-making

---

## 🧰 Tools & Technologies
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, SciPy  
- **Environment:** Jupyter Notebook / Google Colab

---

## 📂 Dataset Overview
The dataset contains 140,000+ restaurant listings from Swiggy with the following features:

| Column             | Description                                |
|--------------------|--------------------------------------------|
| Restaurant Name    | Name of the restaurant                     |
| Cuisine            | Cuisine types                              |
| Rating             | Customer rating (cleaned to numeric)       |
| Number of Ratings  | Count of ratings per restaurant            |
| Average Price      | Average price for two people (₹ cleaned)   |
| Number of Offers   | Number of active offers                    |
| Offer Name         | Textual offer descriptions                 |
| Area               | Local area within the city                 |
| Pure Veg           | Indicates if restaurant is pure veg        |
| Location           | City (e.g., Abohar)                        |

---

## 🔍 Project Workflow

### 🧹 Step 1: Data Cleaning
- Converted ratings, number of ratings, and prices into numeric format
- Removed null values and filled missing categories
- Extracted clean numeric values from strings like "₹200 for two" and "50+ ratings"

### 📊 Step 2: Exploratory Data Analysis (EDA)
- Distribution plots of ratings
- Count plots of top areas
- Boxplots comparing pure veg vs non-veg pricing
- Scatter plots for Rating vs Number of Ratings

### 🧪 Step 3: Hypothesis Testing
- **T-test:** Compared average price between pure veg and non-veg restaurants
- **Chi-square test:** Checked if veg/non-veg status depends on restaurant area

---

## 📈 Key Visualizations
- ⭐ Rating Distribution  
- 🥗 Pure Veg vs Average Price  
- 📍 Top 10 Areas with Most Restaurants  
- 📉 Rating vs Number of Ratings Scatter Plot  

---

## 📊 Results Summary

### ✅ T-Test (Price: Pure Veg vs Non-Veg)
- **P-value = 0.000**
- 🔍 *Significant*: Yes  
💡 *Pure veg and non-veg restaurants have significantly different average prices.*

### ✅ Chi-Square Test (Area vs Pure Veg)
- **P-value = 0.000**
- 🔍 *Significant*: Yes  
💡 *Veg/Non-veg restaurant distribution depends on area.*

---

## 📦 Deliverables
- `EDA_Swiggy_Project.ipynb` – Main notebook with full analysis  
- `swiggy_file.csv` – Cleaned dataset  
- Visualizations embedded in notebook  
- `README.md` – Full project documentation  
- (Optional) `requirements.txt` – Libraries used

---
✨ **Thank you for exploring this project!**  
Feel free to fork ⭐, share feedback, and connect with me on [LinkedIn](https://www.linkedin.com/in/vaishnavi-chakraborty-85b949292)



