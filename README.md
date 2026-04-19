# 📊 SweetViz Data Analysis Project

This project demonstrates **automated Exploratory Data Analysis (EDA)** using the Python library **SweetViz**. It generates a detailed and interactive HTML report for quick insights into datasets.

---

## 🚀 Project Overview

The goal of this project is to:

* Analyze datasets efficiently
* Generate visual insights automatically
* Reduce manual effort in EDA
* Produce a shareable HTML report

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* SweetViz
* Jupyter Notebook

---

## 📂 Project Structure

```
├── Sweetviz.ipynb           # Main notebook for analysis
├── SWEETVIZ_REPORT.html     # Generated EDA report
```

---

## 📊 Features

* Automatic feature analysis
* Correlation detection
* Target variable comparison
* Missing value detection
* Interactive visualizations
* Clean and professional HTML report

---

## ▶️ How to Run the Project

### 1. Install dependencies

```bash
pip install sweetviz pandas
```

### 2. Run Jupyter Notebook

```bash
jupyter notebook
```

### 3. Open and execute:

```
Sweetviz.ipynb
```

---

## 📸 Output

The project generates an interactive report:

👉 `SWEETVIZ_REPORT.html`

You can open this file in any browser to explore:

* Data distributions
* Correlations
* Feature importance
* Data quality insights

---

## 💻 Sample Code

```python
import sweetviz as sv
import pandas as pd

df = pd.read_csv("data.csv")

report = sv.analyze(df)
report.show_html("SWEETVIZ_REPORT.html")
```

---

## 🎯 Use Cases

* Data Science projects
* Machine Learning preprocessing
* Quick dataset understanding
* Business data insights

---

## 📌 Key Learning

* Automated EDA tools
* Data visualization techniques
* Insight extraction from raw data
* Report generation using Python

---

## 🤝 Contributing

Feel free to fork this repository and improve the analysis.

---

## 📄 License

This project is open-source and free to use.
