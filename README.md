# 🍽️ Zomato Data Analysis Using Python

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![License](https://img.shields.io/badge/License-Educational-green)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Zomato Restaurant Dataset** using **Python**. It explores restaurant trends, customer preferences, online ordering behavior, pricing, and ratings through data cleaning, visualization, and statistical analysis.

The notebook demonstrates a complete data analysis workflow—from importing raw data and preprocessing it to generating insightful visualizations and business recommendations.

---

## 🎯 Objectives

- Analyze restaurant categories and their popularity.
- Study customer voting patterns.
- Identify restaurants receiving the highest customer votes.
- Compare online and offline ordering trends.
- Analyze restaurant rating distributions.
- Explore pricing trends for couples.
- Compare ratings based on online ordering availability.
- Visualize relationships between restaurant type and online ordering.

---

## 📂 Dataset

The project uses the **Zomato Restaurant Dataset** provided by **GeeksforGeeks**.

### 📥 Download Dataset

Download the CSV file from:

https://media.geeksforgeeks.org/wp-content/uploads/20250117023324808265/Zomato-data-.csv

Place the downloaded file inside the project directory before running the notebook.

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/ajinkya029/Zomato-Data-Analysis-Using-Python.git
```

### 2. Navigate to the project

```bash
cd Zomato-Data-Analysis-Using-Python
```

### 3. (Optional) Create a virtual environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **Zomato Data Analysis.ipynb** and run all cells.

---

## 📊 Project Workflow

### 1. Data Collection

- Import the dataset into a Pandas DataFrame.

### 2. Data Cleaning

- Handle missing values.
- Convert ratings into numerical format.
- Verify data types.
- Prepare data for analysis.

### 3. Exploratory Data Analysis (EDA)

The notebook includes:

- Restaurant Type Distribution
- Customer Votes Analysis
- Restaurant with Maximum Votes
- Online Order Availability
- Ratings Distribution
- Cost for Two Analysis
- Online vs Offline Ratings
- Restaurant Type vs Online Ordering Heatmap

### 4. Business Insights

Generate actionable insights using statistical analysis and visualizations.

---

## 📈 Visualizations

The notebook includes multiple charts such as:

- 📊 Count Plots
- 📈 Line Charts
- 📉 Histograms
- 📦 Box Plots
- 🔥 Heatmaps

These visualizations help understand customer behavior and restaurant trends effectively.

---

## 🔍 Key Insights

- Dining restaurants are the most common restaurant type.
- Dining restaurants receive the highest number of customer votes.
- Most restaurants do not offer online ordering.
- Restaurant ratings are primarily concentrated between **3.5 and 4.0**.
- Couples generally prefer restaurants costing around **₹300** for two people.
- Restaurants offering online ordering tend to receive slightly higher ratings.
- Dining restaurants rely more on offline customers, while cafés attract relatively more online orders.

---

## 📁 Project Structure

```text
Zomato-Data-Analysis-Using-Python/
│
├── Zomato Data Analysis.ipynb
├── README.md
├── requirements.txt
├── Zomato-data-.csv
└── images/
    ├── restaurant_types.png
    ├── ratings_distribution.png
    ├── online_orders.png
    └── heatmap.png
```

---

## 📚 Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 🚀 Future Improvements

- Develop an interactive Power BI dashboard.
- Create a Tableau dashboard.
- Perform sentiment analysis on customer reviews.
- Build machine learning models to predict restaurant ratings.
- Conduct geospatial analysis using restaurant location data.

---

## 🎓 Learning Outcomes

This project demonstrates practical experience in:

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Business Insight Generation
- Python for Data Analytics

---

## 🤝 Contributing

Contributions are welcome!

To contribute:

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push the branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📄 License

This project is intended for **educational and learning purposes**.

---

## 🙏 Acknowledgements

- GeeksforGeeks for providing the tutorial and dataset.
- The Python open-source community for excellent data analysis libraries.
- The Pandas, NumPy, Matplotlib, and Seaborn development teams.

---

## ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub.

It helps others discover the project and motivates future improvements.
