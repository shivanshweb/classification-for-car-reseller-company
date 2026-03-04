# 🚗 Customer Rebuy Prediction — Car Reseller ML Model

A machine learning classification project that predicts which existing customers are most likely to purchase another car — enabling a car reseller's marketing team to run targeted, cost-efficient campaigns instead of messaging their entire customer base.

---

## 📌 Project Overview

A car reseller company wanted to launch a marketing campaign targeting potential repeat buyers but lacked a data-driven way to identify who to target. This project built a classification model that scores each customer by their likelihood to buy again, producing a ranked list the marketing team can act on directly.

**Problem type:** Binary Classification  
**Tech stack:** Python, scikit-learn, Pandas, Matplotlib

---

## 🎯 Business Question

> *"Which of our existing customers are most likely to buy another car?"*

Without a predictive model, the marketing team would need to contact every customer — most of whom have no intention of buying. This is expensive, inefficient, and damages customer relationships through irrelevant outreach.

With this model, the team can:
- Focus budget on **high-probability customers only**
- Personalise outreach based on customer scoring
- **Increase repeat-sale conversion rates** with the same or lower marketing spend

---

## 🔧 Pipeline Steps

### 1. Data Understanding
- Worked with historical customer records and past purchase data from a car reseller
- Explored customer demographics, purchase history, and behavioural features
- Identified key indicators of repeat purchase behaviour

### 2. Data Preparation
- Cleaned and pre-processed customer and transaction records
- Engineered relevant features from purchase history
- Handled class imbalance between repeat buyers and non-buyers

### 3. Modelling
- Built a **binary classification model** to predict re-buy likelihood (1 = likely to rebuy, 0 = not likely)
- Evaluated multiple classification approaches and selected the best performer
- Scored each customer with a probability of re-purchase

### 4. Output
- Generated a **ranked customer list** sorted by re-buy probability
- Ready to be handed directly to the marketing team for campaign targeting

---

## 💡 Business Impact

- Marketing team can **prioritise the top-scoring customers** rather than contacting everyone
- Reduces wasted marketing spend on customers unlikely to purchase
- Increases **repeat-sale opportunities** by focusing effort where it matters most
- Ranked list is **directly actionable** — no additional analysis required by the marketing team

---

## 📁 Repository Structure

```
├── classification-car-reseller.ipynb   # Main notebook
└── README.md
```

---

## 🚀 How to Run

```bash
# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

# Launch notebook
jupyter notebook classification-car-reseller.ipynb
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| scikit-learn | Classification model, evaluation metrics |
| Pandas / NumPy | Data manipulation and feature engineering |
| Matplotlib / Seaborn | Visualisations |

---

## 👤 Author

**Shivansh Pandey**  
Master of Data Science and Innovation — University of Technology Sydney  
[LinkedIn](https://linkedin.com/in/your-link) | [GitHub](https://github.com/shivanshweb)
