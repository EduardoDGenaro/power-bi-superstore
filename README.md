# 📊 Superstore Sales Dashboard · Power BI

> Exploratory analysis of an American retail chain's sales data from 2015 to 2018, focusing on product categories, customer segments, and regional performance.

---

## 🖼️ Preview

![Dashboard Preview](Preview.png)

---

## 📁 Repository Files

| File | Description |
|---|---|
| `superstore-sales-dashboard.pbix` | Interactive dashboard built in Power BI Desktop |
| `train.csv` | Original dataset with ~9,800 sales records |
| `preview.png` | Dashboard screenshot |

---

## 🔍 What Was Analyzed

- **Sales over time** from 2015 to 2018, broken down by month and quarter
- **Performance by category** — Furniture, Office Supplies, and Technology
- **Distribution by segment** — Consumer, Corporate, and Home Office
- **Regional comparison** — East, West, Central, and South
- **Top sub-categories** by sales volume

---

## 💡 Key Insights

- 📈 **Q4 (October–December)** consistently drives the highest sales peaks across all years
- 💻 **Technology** has the highest average order value, even with fewer total transactions
- 🌎 The **West** region leads in total sales volume, largely driven by California
- 👤 The **Consumer** segment accounts for more than half of all sales

---

## 🛠️ Tools Used

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoft&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

---

## 📐 DAX Measures

```dax
Total Sales = SUM(train[Sales])

Total Orders = DISTINCTCOUNT(train[Order ID])

Average Ticket = DIVIDE([Total Sales], [Total Orders])
```

---

## 📦 Data Source

Public dataset **Sample - Superstore** available on [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final).

- ~9,800 transaction rows
- 18 columns (date, product, customer, location, sales)
- Period: 2015–2018 · Market: United States

---

## 👤 Author

Made by **Eduardo** · Systems Analysis and Development Student
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/eduardo-davi-genaro-185599406)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/EduardoDGenaro)
