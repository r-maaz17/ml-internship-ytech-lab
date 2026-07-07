# 🧪 ML Internship Lab — Y-Tech Labs

A structured collection of machine learning notebooks covering real-world datasets, preprocessing pipelines, and model evaluation across 7 weeks of applied ML internship at **Y-Tech Labs**.

---

## 👤 Author
**Muhammad Moaz**  
BS Computer Science — University of Engineering & Technology, Lahore  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)][(https://linkedin.com/in/muhammad-moaz381/)]
[![GitHub](https://img.shields.io/badge/GitHub-black?style=flat&logo=github)](https://github.com/r-maaz17)

---

## 📁 Repository Structure

```
ml-internship-lab/
│
├── Week1_EDA_Iris/
│   └── iris_eda.ipynb                  # EDA, feature engineering & visualization on Iris dataset
│
├── Week2_EDA_RealWorld/
│   ├── air_quality_eda.ipynb           # Air quality trends & pollutant analysis
│   ├── video_game_sales_eda.ipynb      # Market trends in video game sales
│   └── world_happiness_eda.ipynb       # Happiness factors across countries
│
├── Week3_NLP_PDF_Parsing/
│   ├── extract_pdf_metadata.py         # Automated PDF metadata extraction pipeline
│   └── dataset.csv                     # Extracted structured dataset from 22 policy documents
│
├── Week4_Heart_Disease_Analysis/
│   └── heart_disease_analysis.ipynb    # EDA & risk factor analysis on heart disease data
│
├── Week5_Supervised_Unsupervised_ML/
│   ├── iris_supervised_learning.ipynb  # KNN, Decision Tree, Logistic Regression on Iris
│   └── mall_customer_clustering.ipynb  # K-Means, DBSCAN, Hierarchical Clustering
│
├── Week6_Anomaly_Detection/
│   └── fraud_detection.ipynb           # Isolation Forest, LOF, One-Class SVM on credit card fraud
│
├── Week7_Spectroscopy/
│   └── spectroscopy_classification.ipynb  # NIR/MIR preprocessing & classification pipelines
│
└── README.md
```

---

## 📌 Weekly Breakdown

### Week 1 — EDA & Feature Engineering
- Explored the classic **Iris dataset** using Pandas & NumPy
- Created visualizations: scatter plots, histograms, box plots & pair plots
- Engineered new features: petal area, sepal area, length & width ratios

### Week 2 — Real-World EDA
- **Air Quality:** Identified traffic-driven pollution patterns & seasonal trends
- **Video Game Sales:** Analyzed genre, platform & publisher impact on global sales
- **World Happiness:** Investigated GDP, social support & freedom as happiness drivers

### Week 3 — NLP & PDF Parsing
- Built an automated pipeline using `pdfplumber` & `Regex`
- Extracted structured metadata (title, author, dates, document type) from **22 NHS policy PDFs**
- Output: clean CSV dataset with `nan` handling for missing fields

### Week 4 — Heart Disease Analysis
- Performed EDA on UCI Heart Disease dataset
- Identified key risk factors: chest pain type, max heart rate, ST depression
- Extended analysis with age-group stratification & gender-based comparisons

### Week 5 — Supervised & Unsupervised Learning
- **Supervised:** KNN, Decision Tree, Logistic Regression on Iris — evaluated with accuracy & F1-score
- **Unsupervised:** K-Means, Hierarchical Clustering, DBSCAN on Mall Customers — evaluated with silhouette score & Calinski-Harabasz index

### Week 6 — Anomaly Detection
- Applied **Isolation Forest**, **Local Outlier Factor**, and **One-Class SVM** on Kaggle Credit Card Fraud dataset (284,807 transactions, 492 frauds)
- Evaluated with Precision, Recall, F1-score & ROC-AUC
- Isolation Forest achieved best ROC-AUC & recall

### Week 7 — Spectroscopy Classification
- Preprocessed **NIR Mango** & **MIR Fruit Purees** spectroscopy datasets
- Applied Savitzky-Golay smoothing & L2 vector normalization
- Benchmarked **6 pipeline combinations** with K-Means & Random Forest
- Best pipeline: SG Smoothing → L2 Normalization → Random Forest

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python 3.x |
| Data & EDA | Pandas, NumPy, Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| NLP & Parsing | pdfplumber, Regex |
| Signal Processing | SciPy (Savitzky-Golay), L2 Normalization |
| Environment | Jupyter Notebook / Google Colab |

---

## ⚙️ Setup & Usage

```bash
# Clone the repository
git clone https://github.com/yourusername/ml-internship-lab.git
cd ml-internship-lab

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn pdfplumber scipy jupyter

# Launch Jupyter
jupyter notebook
```

> Each folder is self-contained. Open any `.ipynb` file and run cells sequentially.

---

## 📊 Key Results

| Task | Algorithm | Best Metric |
|---|---|---|
| Iris Classification | Logistic Regression | Accuracy: 93.3% |
| Customer Clustering | K-Means (k=5) | Silhouette: 0.417 |
| Fraud Detection | Isolation Forest | ROC-AUC: 0.97+ |
| Spectroscopy | SG → Norm → RF | Highest CV Accuracy |

---

## 🏢 About Y-Tech Labs

This internship was completed at **Y-Tech Labs** as part of a structured 7-week applied ML program.  
*Certificate of Experience issued by Y-Tech Labs — July 2024 to August 2024.*

---

## 📄 License

This repository is for educational and portfolio purposes.  
© 2024 Muhammad Moaz — All rights reserved.
