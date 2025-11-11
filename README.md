# 🎬 Movie Budget vs. Revenue Analysis

This project explores whether bigger film budgets lead to higher box office revenues, using historical data scraped from [The Numbers](https://www.the-numbers.com/movie/budgets) as of May 1, 2018.

We cleaned, transformed, and analyzed the data, then built a linear regression model to examine the relationship between production budgets and worldwide revenue. Key visualizations were built using Seaborn and Plotly.

---

## 📊 Key Highlights

- Converted release dates to decades for temporal trend analysis  
- Analyzed summary statistics (e.g., average revenue, profitability thresholds)  
- Filtered international-only releases and extreme budget outliers  
- Built regression plots to visualize budget–revenue relationship  
- Investigated patterns in new vs. older films

---

## 📁 Dataset Info

- Source: [The Numbers - Movie Budgets](https://www.the-numbers.com/movie/budgets)
- Scraped: May 1st, 2018
- Contains:  
  - Release Dates  
  - Production Budgets  
  - Domestic & Worldwide Gross  

---

## ⚙️ Tech Stack

- Python (Pandas, NumPy, Seaborn, Matplotlib, Plotly)
- Jupyter Notebook
- Regression modeling

---

## 📌 Outcome

The analysis shows a clear (though not perfect) positive relationship between production budget and revenue. However, some films with massive budgets underperformed, while others exceeded expectations despite modest budgets.

---

## 📎 License

This project is for educational and non-commercial use.
