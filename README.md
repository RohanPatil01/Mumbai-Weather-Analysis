# 🌦️ Mumbai Weather Analysis (1990–2022)

This project presents an exploratory data analysis (EDA) of historical weather data from Mumbai, India, spanning over three decades (1990–2022). The goal is to understand long-term patterns in temperature and rainfall, highlight seasonal behavior, and identify anomalies in the city's climate.

## 📌 Project Objective

- Analyze historical weather data of Mumbai.
- Detect trends and outliers in temperature and rainfall.
- Understand seasonal climate behavior using visualizations.

---

## 📁 Files in the Repository

| File/Folder | Description |
|-------------|-------------|
| `Mumbai Weather Analysis.ipynb` | Jupyter Notebook with complete data analysis |
| `Data/Mumbai_1990_2022_Santacruz.csv` | Dataset used (if included) |
| `requirements.txt` | Python dependencies |
| `README.md` | This file |

---

## 📊 Key Features of the Analysis

- **Data Cleaning:** Missing values handled, datetime formatting, indexing.
- **Visual Explorations:** Line plots, correlation plots, bar charts for weather metrics.
- **Insights:** 
  - Monsoon peaks in July with highest rainfall.
  - Winters (Dec–Feb) are coolest, summers are long and intense.
  - Abnormal rainfall spikes detected in 2014, 2019, and 2021.

---

## 🧪 Libraries Used

- `pandas` – data wrangling  
- `numpy` – numerical computations  
- `matplotlib` & `seaborn` – data visualization  
- `missingno` – visualizing missing values  
- `datetime` – time parsing and formatting

---

## 📦 Installation

Clone this repository and install the required libraries:

```bash
git clone https://github.com/yourusername/mumbai-weather-analysis.git
cd mumbai-weather-analysis
pip install -r requirements.txt
````

---

## 🚀 How to Run

Make sure you have Jupyter Notebook or JupyterLab installed. Then run:

```bash
jupyter notebook "Mumbai Weather Analysis.ipynb"
```

---

## ✅ Insights

* **Mumbai's monsoon** is concentrated between June and September, with **July** being the wettest.
* **Heat waves** observed in pre-monsoon months like March–May.
* **Climate anomalies** in 2019 and 2021 signal abnormal rainfall outside monsoon season.

---

## ⚠️ Notes

* Do not rerun the cell where `time` column is dropped unless you've reloaded the dataset.
* The dataset used here represents a **single weather station** (Santacruz), so results may not generalize across all of Mumbai.

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
