# 🧠 Health Monitoring Dataset Analysis

A comprehensive **Exploratory Data Analysis (EDA)** project focused on analyzing **mental health patterns using wearable device data**.  
This project investigates relationships between physiological metrics and mental health indicators using statistical analysis and visualization.

---

## 📊 Project Overview

Wearable devices generate large amounts of physiological data such as:

- Heart Rate
- Sleep Patterns
- Activity Levels
- Stress Indicators

This project analyzes such data to understand **patterns affecting mental health and wellbeing**.

The notebook performs a **complete data analysis pipeline**, including:

- Dataset exploration
- Data quality assessment
- Statistical analysis
- Correlation studies
- Outlier detection
- Feature importance analysis
- Dimensionality reduction using PCA

---

## 🧰 Technologies Used

| Tool | Purpose |
|-----|------|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning utilities |
| SciPy | Statistical analysis |

---

## 📁 Project Structure

```
Health-Monitoring-Analysis
│
├── Health_monitoring_dataset_analysis.ipynb
│
├── dataset
│   └── mental_health_wearable_data.csv
│
└── README.md
```

---

## 🔍 Analysis Workflow

### 1️⃣ Dataset Overview
- Understanding dataset structure
- Data types inspection
- Summary statistics

---

### 2️⃣ Data Quality Assessment
Checks for:

- Missing values
- Invalid entries
- Data consistency

---

### 3️⃣ Univariate Analysis
Examines individual features using:

- Histograms
- Distribution plots
- Statistical summaries

---

### 4️⃣ Target Variable Analysis
Focuses on the **mental health indicator variable**, analyzing:

- Class distribution
- Behavioral patterns

---

### 5️⃣ Correlation Analysis
Identifies relationships between variables using:

- Correlation matrices
- Heatmaps

This helps determine which physiological signals relate to mental health.

---

### 6️⃣ Multicollinearity Detection
Detects redundant features that may affect model performance.

Techniques used:

- Correlation threshold analysis
- Variance evaluation

---

### 7️⃣ Bivariate Analysis
Studies relationships between pairs of variables using:

- Scatter plots
- Pair plots
- Comparative distributions

---

### 8️⃣ Outlier Detection
Detects abnormal values using:

- Statistical thresholds
- Distribution analysis

Outliers may indicate **rare health conditions or sensor anomalies**.

---

### 9️⃣ Mutual Information Analysis
Measures **feature importance** relative to the target variable.

This identifies which physiological signals contribute most to mental health prediction.

---

### 🔟 Principal Component Analysis (PCA)
Reduces feature dimensionality while preserving variance.

Benefits:

- Simplifies complex datasets
- Identifies hidden patterns
- Improves machine learning efficiency

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/health-monitoring-analysis.git
```

### 2️⃣ Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

### 3️⃣ Run the notebook

```bash
jupyter notebook
```

Open:

```
Health_monitoring_dataset_analysis.ipynb
```

---

## 💡 Future Improvements

- Build **mental health prediction models**
- Implement **real-time wearable data analysis**
- Develop **health monitoring dashboards**
- Deploy using **Streamlit or Flask**

---

## 👨‍💻 Author

**Sajeesh K (Sajeev)**  
B.Tech Computer Science – AI & ML  
Lovely Professional University

Skills:
- Machine Learning
- Data Analysis
- Python
- React
- Node.js
- Docker
- C++
- Java

---

⭐ If you like this project, consider giving it a **star on GitHub**!
