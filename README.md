Analysis of real-world marketing dataset to understand which customer segments responded to the last campaign. Includes visualisations, statistical testing and actionable insights.

# Marketing Campaign Analysis

This project analyses customer data from a marketing campaign to understand which groups were more likely to respond. The goal is to help marketing teams target future campaigns more effectively.

---

## Objective
**Question:** Did our recent campaign lead to more conversions, and who is most likely to respond?

---

## Tools Used
- Python
- pandas
- seaborn
- matplotlib
- scipy.stats

---

## Dataset
- File: `marketing_campaign.csv`
- Size: ~2,200 customers
- Key features: `Income`, `Education`, `Marital_Status`, `Recency`, `Response` (target)

---

## Analysis Steps
- Cleaned missing data (especially `Income`)
- Visualised differences in:
  - Income vs Response
  - Education vs Response
  - Marital Status vs Response
  - Recency vs Response
- Used a **t-test** to compare income between responders and non-responders

---

## Key Insights
- Customers contacted **more recently** were more likely to respond
- **Higher-income** customers responded at a significantly higher rate (p < 0.001)
- **Education** and **marital status** showed patterns worth exploring further

---

## How to Run
1. Open the notebook in Google Colab or Jupyter
2. Upload `marketing_campaign.csv`
3. Run all cells

---

## Future Improvements
- Add logistic regression to predict responses
- Automate generation of plots + summaries
