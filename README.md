# Hi there, I'm Rahul Maheshwari 👋

### 🎓 B.Tech CSE (IoT) Student | 📍 Rajasthan, India | 🔍 Seeking Data Science Internship

---

## 🧠 About Me

- 🔥 Passionate about **Machine Learning, Deep Learning and Data Science**
- 🏗️ I love building end-to-end ML projects — from raw data to deployed models
- 📊 Strong believer in **data-driven decision making**
- 🏓 2x State Level Table Tennis Player — I bring the same competitive drive to everything I do
- 🌱 Currently learning **CNNs, NLP and Flask deployment**
- 💡 Always curious, always building

---

## 🏆 Achievements & Competitions

### 🛒 [Flipkart Gridlock Hackathon 2.0](https://www.hackerearth.com/) — *June 2026*
> AI/ML hackathon on HackerEarth in partnership with Bengaluru Traffic Police to solve urban mobility challenges

| Metric | Detail |
|--------|--------|
| 🎯 **Score** | **90.66** |
| 🏅 **Rank** | **4,121** out of ~10,000 participants |
| 🧠 **Focus** | AI-driven traffic & urban mobility solutions |
| 🏢 **Organized by** | Flipkart × Bengaluru Traffic Police |

---

## 🛠️ Tech Stack

**Languages & Query:**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

**ML & Deep Learning:**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge&logo=lightgbm&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Visualization & BI:**

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Tools & Deployment:**

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

## 🚀 Machine Learning & Data Science Projects

### 🫀 [Heart Disease Risk Prediction — PyTorch ANN](https://github.com/RahulMaheshwari12/Heart-Disease-Risk-Prediction-PyTorch-ANN)
`Python` `PyTorch` `Flask` `SQLite3` `Scikit-Learn`
> End-to-end heart disease prediction on 630,000 patient records

- 🗄️ Built a complete **SQL data pipeline** using SQLite3 for EDA — queries covering demographics, clinical features & multi-factor risk combinations
- 🔧 Performed **data cleaning, preprocessing & feature selection** — dropped zero-correlation params; engineered 3 domain features with leakage-safe ColumnTransformer
- 🤖 **PyTorch ANN** (BatchNorm + Dropout + LeakyReLU) with WeightedRandomSampler — **ROC-AUC: 0.9538 | 91.35% recall**, outperforming baseline by 3.35%
- 🌐 **Threshold tuned at 0.4** for medical recall; served predictions via **Flask web application**

---

### 📉 [Customer Churn Prediction & Retention Dashboard](https://github.com/RahulMaheshwari12/coustmer-churn-prediction)
`Python` `LightGBM` `Flask` `Scikit-Learn` `Pandas` `JavaScript` `Chart.js`
> End-to-end predictive pipeline on 304,000 customer records with interactive Flask dashboard

- 🎯 Achieved **88% recall** and **Class-1 F1-score: 0.69** using optimized **LightGBM** ensemble to address class imbalance
- 🔧 Custom **data preprocessing** with ColumnTransformer — Ordinal/OneHot encoding + specialized scalers (**PowerTransformer** Yeo-Johnson for skewed billing, **MinMaxScaler** for bimodal tenure)
- ⚙️ Optimized hyperparameters via **RandomizedSearchCV** over Stratified K-Fold cross-validation; extracted feature importances for key attrition drivers
- 🎨 **Flask dashboard** with real-time animated **SVG risk gauges**, risk explanations & drag-and-drop batch CSV upload visualized via **Chart.js**

---

### 💳 [Credit Risk & Loan Default Prediction](https://github.com/RahulMaheshwari12/Credit-Risk-Classification-Pipeline-prediction)
`Python` `Scikit-Learn` `Pandas`
> End-to-end binary classification pipeline on LendingClub financial data

- 🛡️ **Data leakage prevention** — dropped 25+ post-origination features
- 🔧 **Feature engineering** — installment-to-income ratio, utilization-per-account & data cleaning on financial datasets
- ⚙️ Tuned ML algorithms via **GridSearchCV** with 5-fold **cross-validation**
- 🎯 **ROC-AUC: 0.71** with business-driven **threshold tuning** (0.4 to maximize recall)

---

## 📊 Data Analysis Project

### 🎬 [Netflix Data Analysis](https://github.com/RahulMaheshwari12/Netflix-data-analysis)
`Python` `Pandas` `Seaborn` `Matplotlib`
> Exploratory analysis of 8,800+ Netflix titles uncovering content trends

- 📊 **11 visualizations** including year×month heatmap for content additions
- 🔍 Analyzed content growth trends, genre distribution & rating patterns
- 🧹 Data cleaning — datetime conversion, missing value handling, genre splitting
- 📈 Insights on Movies vs TV Shows distribution & country-wise content analysis

---

## 📜 Certifications

- 🏅 **Data Science with AI** — Internshala × IITM Pravartak Technologies Foundation (April 2026)
- 🏅 **Certificate Program in Data Science** — Skill India / NSDC × Scholiverse Educare | Grade A (April 2026)

---

## 🤝 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahulmaheshwari73)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RahulMaheshwari12)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahulmaheshwari529@gmail.com)

---

⭐ *"Data is the new oil — I'm here to refine it."*
