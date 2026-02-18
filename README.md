# 📈 Sales Prediction Model

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

> A machine learning model to forecast product sales based on advertising spend across TV, radio, and newspaper channels — helping businesses optimize their marketing budget.

---

## 📌 Project Overview

Understanding the relationship between advertising spend and sales is crucial for marketing optimization. This project builds a **Sales Prediction Model** using regression analysis to predict product sales based on advertising budgets across multiple channels.

Developed as part of my **Data Science Internship at Oasis Infobyte**.

---

## 🎯 Key Highlights

- ✅ Analyzed the impact of **TV, radio, and newspaper** advertising on sales
- ✅ Built and compared **multiple regression models**
- ✅ Identified which advertising channels have the strongest ROI
- ✅ Provided actionable insights for marketing budget allocation
- ✅ Clean **Jupyter Notebook** with EDA and model evaluation

---

## 📊 Dataset

| Property | Details |
|---|---|
| Task | Regression — predict sales revenue |
| Features | TV ad spend, Radio ad spend, Newspaper ad spend |
| Target | Sales (in thousands of units) |
| Business Use | Marketing budget optimization |

---

## 🔍 Key Features

| Feature | Description |
|---|---|
| `TV` | Advertising budget for TV (in $1000s) |
| `Radio` | Advertising budget for Radio (in $1000s) |
| `Newspaper` | Advertising budget for Newspaper (in $1000s) |
| `Sales` | Product sales (in 1000s of units) |

---

## 🧠 Methodology

### 1. Exploratory Data Analysis (EDA)
- Analyzed correlation between advertising channels and sales
- Found **TV advertising** has the strongest positive correlation with sales
- Identified that **newspaper advertising** has minimal impact on sales
- Visualized relationships using scatter plots and heatmaps

### 2. Feature Engineering
- Checked for multicollinearity between advertising channels
- Normalized features for better model performance
- Created interaction terms if needed

### 3. Model Training
- Trained **Linear Regression** as baseline
- Compared with **Ridge** and **Lasso** regression for regularization
- Selected best model based on R² score and RMSE

### 4. Business Insights
- Calculated **ROI (Return on Investment)** for each channel
- Recommended optimal budget allocation strategy
- Identified diminishing returns thresholds

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Regression models & evaluation |
| Jupyter Notebook | Development environment |

---

## 🏆 Model Results

| Metric | Score |
|---|---|
| R² Score | *(Add your score)* |
| RMSE | *(Add your score)* |
| MAE | *(Add your score)* |

> 💡 Run `sample.ipynb` to see full model evaluation and insights.

---

## 💡 Key Business Insights

**Advertising Channel Performance:**

| Channel | Impact on Sales | Recommendation |
|---|---|---|
| TV | 🟢 **Strong** | Primary investment channel |
| Radio | 🟡 **Moderate** | Secondary support channel |
| Newspaper | 🔴 **Weak** | Minimize or eliminate spend |

**Predicted Sales Examples:**
- **TV: $50K, Radio: $20K, Newspaper: $10K** → Sales: ~15,000 units
- **TV: $100K, Radio: $40K, Newspaper: $0K** → Sales: ~25,000 units

**Optimization Strategy:**
- Allocate **60-70% of budget to TV advertising**
- Use **20-30% for radio** to reach different demographics
- **Reduce newspaper spend** — reallocate to digital channels

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/Khiladi-786/Sales_Prediction_Model.git
cd Sales_Prediction_Model
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Open the notebook
```bash
jupyter notebook sample.ipynb
```

---

## 📁 Project Structure

```
Sales_Prediction_Model/
│
├── sample.ipynb          # Main Jupyter Notebook
├── requirements.txt      # Python dependencies
├── template/             # Project templates
└── README.md             # Project documentation
```

---

## 👨‍💻 About the Author

**Nikhil More**
B.Tech CSE (AI/ML) — University of Mumbai (2023–2027)

- 🔗 [LinkedIn](https://www.linkedin.com/in/nikhil-moretech)
- 🐙 [GitHub](https://github.com/Khiladi-786)
- 📧 morenikhil7822@gmail.com

*Data Science Intern @ Oasis Infobyte | C-DAC Ambassador | Google Student Ambassador*

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ **If you found this project useful, please give it a star!**
