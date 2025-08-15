# 🏅 Decoding Olympic Glory (1896–2021)

A data-driven exploration of **Olympic Games history** from **Athens 1896** to **Tokyo 2021**, uncovering trends in **medal counts**, **gender participation**, **sport diversity**, and **country performance efficiency** — complemented with a predictive model to estimate future medal tallies.

---

## 📌 Project Overview

The Olympic Games have been a global sporting spectacle for over a century. This project combines **data analysis**, **visualization**, and **machine learning** to:

- Explore **historical trends** in Olympic medal counts and participation.
- Investigate **gender representation** in sports over time.
- Identify **top-performing nations** and their medal efficiency.
- Build and evaluate a **predictive model** for future medal counts.

The project is divided into two main parts:
1. **Exploratory Data Analysis (EDA)** – Understanding the dataset and extracting insights.
2. **Machine Learning Modeling** – Predicting medal counts using historical data.

---

## 📂 Project Structure
Decoding-Olympic-Glory-1896-2021/
│
├── notebooks/
│ ├── eda.ipynb # Data cleaning, EDA, and visualizations
│ ├── model.ipynb # Machine learning model training and evaluation
│ └── data/olympics_data.csv # Raw dataset
│
├── model/
│ └── best_model.pkl # Saved trained ML model
│
├── images/ # Project visualizations
│ ├── gender split of medals by sport.png
│ ├── medal count over time for selected country.png
│ ├── participation by gender over the years.png
│ ├── top 10 countries by total medals.png
│ └── ...
│
├── README.md # Project documentation
└── requirements.txt # Python dependencies


---

## 📊 Key Analyses & Insights

### 1. **Top 10 Countries by Total Medals**
- Bar charts showing the nations with the most cumulative Olympic success.

### 2. **Total Medals Over the Years**
- Line plot tracking the evolution of total medals awarded.

### 3. **Gender Participation Trends**
- Visualization of how male and female participation has evolved.

### 4. **Medal Efficiency**
- Medals won per athlete — highlighting countries with high efficiency despite smaller delegations.

### 5. **Sport-Specific Performance**
- Medal distributions by sport and gender.

---

## 🤖 Machine Learning Component

**Goal:** Predict the number of medals a country might win in a future Olympics based on historical performance.

**Workflow:**
1. Feature engineering from historical medal and participation data.
2. Model selection (e.g., Random Forest, Gradient Boosting).
3. Hyperparameter tuning.
4. Model evaluation (MAE, RMSE, R²).
5. Export of best-performing model (`best_model.pkl`).

---

## 🛠 Tech Stack

- **Python 3.8+**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Machine learning
- **Jupyter Notebook** – Interactive development

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/Decoding-Olympic-Glory-1896-2021.git
cd Decoding-Olympic-Glory-1896-2021


📈 Results & Findings

USA consistently dominates medal counts.

Gender equality in participation has improved significantly post-1990s.

Smaller nations like Jamaica and Kenya have exceptional medal efficiency.

Predictive model achieves X% accuracy in medal count prediction.

