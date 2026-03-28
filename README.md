# 🛒 Superstore Sales Analysis

A complete exploratory data analysis (EDA) of the Kaggle Superstore dataset using **Python**, uncovering key business insights around sales, profit, customer segments, and product performance.

---

## 📌 Objective

To analyze retail sales data and answer critical business questions:
- Which months drive the highest sales and profit?
- Which product categories and sub-categories perform best?
- Which customer segment is most valuable?
- How efficient is profit generation across segments?

---

## 🛠️ Tools & Libraries Used

| Tool | Purpose |
|------|---------|
| Python | Core analysis |
| Pandas | Data loading, cleaning, transformation |
| Plotly Express | Interactive charts & visualizations |
| Plotly Graph Objects | Custom grouped bar charts |
| Google Colab | Development environment |

---

## 📂 Project Structure

```
superstore-sales-analysis/
│
├── Analysis_of_super_store.ipynb   ← Main Python Notebook (EDA + Visualizations)
├── README.md                       ← Project documentation
└── dataset_source.md               ← Dataset info & Kaggle link
```

---

## 📊 Analysis Performed

### 1. Monthly Sales Analysis
- Plotted monthly sales trend using a **line chart**
- **November** → Peak sales month (holiday/Black Friday season)
- **February** → Lowest sales month

### 2. Sales by Category
- Visualized using a **donut/pie chart**
- **Technology** leads in total sales
- **Office Supplies** has the lowest sales (high volume, low value items)

### 3. Sales by Sub-Category
- Visualized using a **bar chart**
- **Phones** top the sub-category chart
- **Fasteners** contribute the least

### 4. Monthly Profit Analysis
- Plotted using a **line chart**
- **December** → Highest profit (festive season + year-end)
- **January** → Lowest profit (post-holiday slowdown)

### 5. Profit by Category & Sub-Category
- **Technology** is the most profitable category
- **Furniture** is the least profitable
- **Copiers** lead among sub-categories
- **Tables, Bookcases, and Supplies** show **negative profit** ⚠️

### 6. Sales & Profit by Customer Segment
- Compared using a **grouped bar chart**
- **Consumer** segment leads in both sales and profit
- **Home Office** contributes the least

### 7. Sales-to-Profit Ratio by Segment
- **Home Office** is the most efficient (ratio: 7.13)
- **Consumer** has the highest ratio (8.66) — high sales, lower per-sale profitability

---

## 💡 Key Business Insights

1. **Focus Q4 marketing** — November and December are peak months
2. **Re-evaluate Furniture pricing** — Tables and Bookcases are running at a loss
3. **Invest in Technology** — Highest sales and profit category
4. **Home Office is underrated** — Small segment but most profit-efficient
5. **Phones drive sub-category revenue** — Strong upsell/cross-sell opportunity

---

## 📁 Dataset

- **Source:** [Kaggle - Sample Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Records:** 9,994 rows | 21 columns
- **Encoding:** latin-1

---

## 👤 Author

**Kamal Singh**
- 🎓 M.Com in Applied Business Economics, St. John's College, Agra
- 📊 Data Analyst | SQL • Power BI • Excel • Python
- 🔗 [LinkedIn](https://linkedin.com/in/kamal-singh-2941ab329)

---

*This project is part of my data analyst portfolio built using real-world retail data.*
