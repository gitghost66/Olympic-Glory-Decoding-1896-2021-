# 🏅 Decoding Olympic Glory (1896–2021)

This project offers a comprehensive, data-driven exploration of the **history of the Olympic Games** from **Athens 1896** to **Tokyo 2021**. It uncovers trends in **medal counts**, **gender participation**, **sport diversity**, and **country performance efficiency**, and includes a predictive model to estimate future medal tallies.

---

## 📌 Project Overview

The Olympic Games have captivated audiences worldwide for over a century. This project integrates **data analysis**, **visualization**, and **machine learning** to achieve the following objectives:

- Analyze **historical trends** in Olympic medal counts and athlete participation.
- Examine **gender representation** in various sports over time.
- Identify **top-performing nations** and assess their medal efficiency.
- Develop and assess a **predictive model** for estimating future medal counts.

The project is structured into two primary components:
1. **Exploratory Data Analysis (EDA)** – Gaining insights from the dataset through exploration and visualization.
2. **Machine Learning Modeling** – Utilizing historical data to predict future medal counts.

---

## 📂 Project Structure

```
Decoding-Olympic-Glory-1896-2021/
│
├── notebooks/
│   ├── eda.ipynb                # Data cleaning, EDA, and visualizations
│   ├── model.ipynb              # Machine learning model training and evaluation
│   └── data/olympics_data.csv    # Raw dataset
│
├── model/
│   └── best_model.pkl            # Saved trained ML model
│
├── images/                       # Project visualizations
│   ├── gender_split_of_medals_by_sport.png
│   ├── medal_count_over_time_for_selected_country.png
│   ├── participation_by_gender_over_the_years.png
│   ├── top_10_countries_by_total_medals.png
│   └── ...
│
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies
```

---

## 📊 Key Analyses & Insights

### 1. **Top 10 Countries by Total Medals**
- Bar charts illustrating the nations with the highest cumulative Olympic success.

### 2. **Total Medals Over the Years**
- A line plot depicting the evolution of total medals awarded throughout the years.

### 3. **Gender Participation Trends**
- Visualizations showcasing the progression of male and female participation in the Olympics.

### 4. **Medal Efficiency**
- Analysis of medals won per athlete, highlighting countries that achieve high efficiency with smaller delegations.

### 5. **Sport-Specific Performance**
- Distribution of medals by sport and gender, providing insights into performance across different disciplines.

---

## 🤖 Machine Learning Component

**Objective:** To predict the number of medals a country may win in future Olympic Games based on historical performance data.

**Workflow:**
1. Feature engineering from historical medal and participation datasets.
2. Model selection (e.g., Random Forest, Gradient Boosting).
3. Hyperparameter tuning for optimal performance.
4. Model evaluation using metrics such as MAE, RMSE, and R².
5. Exporting the best-performing model as `best_model.pkl`.

---

## 🛠 Tech Stack

- **Python 3.8+**
- **Pandas, NumPy** – For data manipulation
- **Matplotlib, Seaborn** – For data visualization
- **Scikit-learn** – For machine learning
- **Jupyter Notebook** – For interactive development

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/Decoding-Olympic-Glory-1896-2021.git
cd Decoding-Olympic-Glory-1896-2021
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Explore the EDA Notebook
```bash
jupyter notebook notebooks/eda.ipynb
```

### 4️⃣ Run the Model Notebook
```bash
jupyter notebook notebooks/model.ipynb
```

### 📈 Results & Findings
- The USA consistently leads in total medal counts.
- Gender equality in participation has significantly improved since the 1990s.
- Smaller nations like Jamaica and Kenya exhibit remarkable medal efficiency.
- The predictive model achieves an accuracy of X% in forecasting medal counts.

--- 

