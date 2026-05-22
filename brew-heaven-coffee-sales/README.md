# ☕ Brew Heaven Coffee Sales Dashboard

> Power BI sales dashboard analysing orders, customer behaviour, inventory, and feedback for a fictional coffee shop.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

[← Back to Portfolio](../README.md)

---

## 📊 Dashboard preview

> _Screenshot coming soon — export from Power BI and place in `/screenshots/`_
> `![Dashboard Screenshot](screenshots/brew-heaven-dashboard.png)`

---

## 📌 Project summary

This dashboard explores sales performance, customer loyalty, and inventory health for **Brew Heaven** — a fictional coffee shop. The dataset covers 50 orders placed by 5 repeat customers across multiple product categories, alongside customer feedback scores and live inventory levels.

**Dataset covers:**
- Order history (Order IDs 301–350)
- 5 products across two suppliers (BeanWorld, PastryPro)
- Customer feedback ratings (1–5 scale)
- Inventory levels with reorder thresholds

---

## 🔍 Key insights

- **Customer 201 (John Doe) is the most loyal buyer** — appearing in over 10 orders and purchasing across multiple product types consistently.
- **Product 103 drives the highest revenue per order** — priced at $4/unit and frequently ordered in quantities of 2–4.
- **Inventory for Product 103 is critically low** — stock at 30 units against a reorder level of 20, the closest to needing a restock.
- **Average customer rating is 4.2 / 5** — generally positive, with complaints focused on temperature and freshness rather than service.

---

## 🛠️ Tools used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Data modelling, DAX measures, report building |
| Microsoft Excel | Source data (Orders, Customers, Inventory, Feedback) |
| Power Query | Data transformation and relationship setup |

---

## 📁 Files

```
brew-heaven-coffee-sales/
│
├── Brew_Heaven_Coffee_Sales_Dashboard.pbix   ← Power BI report
├── data/
│   └── brew_heaven_data.xlsx                 ← Source dataset
├── screenshots/
│   └── brew-heaven-dashboard.png             ← Dashboard preview
└── README.md
```

---

## ▶️ How to view

1. Download `Brew_Heaven_Coffee_Sales_Dashboard.pbix`
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Data is embedded — no additional setup needed
