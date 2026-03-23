# 🚗 Car Sales Dashboard — Tableau Project

An interactive **Car Sales Analytics Dashboard** built in Tableau, providing Year-to-Date (YTD) insights into sales performance, pricing trends, vehicle distribution, and dealer region metrics.

---

## 📊 Dashboard Overview

| KPI | Value |
|-----|-------|
| YTD Total Sales | $371.19M |
| YoY Growth (Sales) | +23.59% |
| YTD Cars Sold | 13,260 |
| YoY Growth (Cars Sold) | +24.57% |
| YTD Avg Price | $27.99K |
| YoY Growth (Avg Price) | -0.79% |

---

## 📋 Problem Statement

The dashboard addresses five core business questions:

1. **YTD Sales Weekly Trend** — Line chart showing weekly sales volume over time
2. **YTD Total Sales by Body Style** — Pie chart breaking down sales by vehicle body type (SUV, Sedan, Hatchback, etc.)
3. **YTD Total Sales by Colour** — Donut chart showing colour-wise sales contribution
4. **YTD Cars Sold by Dealer Region** — Bar chart visualising geographic sales distribution
5. **Company-Wise Sales Trend (Grid)** — Tabular view of each company's YTD cars sold, avg price, total sales, and % share

---

## 🗂️ Repository Structure

```
car-sales-dashboard/
├── README.md
├── .gitignore
├── data/
│   ├── Car_Sales.pdf             # Source data reference
│   └── data_dictionary.md        # Field descriptions
├── dashboard/
│   └── Car_Sales_Dashboard.twbx  # Tableau packaged workbook
├── docs/
│   ├── problem_statement.md      # Business requirements
│   └── insights.md               # Key findings & takeaways
└── assets/
    └── screenshots/
        └── dashboard_preview.png # Dashboard screenshot
```

---

## 🛠️ Tools & Technologies

- **Tableau Desktop / Tableau Public** — Dashboard development
- **Data Source** — Car Sales dataset (2020–2021)
- **Filters** — Date range, Transmission, Body Style, Engine type, Gender

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/car-sales-dashboard.git
   cd car-sales-dashboard
   ```

2. Open the Tableau workbook:
   - Launch **Tableau Desktop** or **Tableau Public**
   - Open `dashboard/Car_Sales_Dashboard.twbx`

3. Explore the dashboard using the **Filter Panel** on the left side

---

## 📈 Key Insights

- **SUV** leads body style sales at **$99.89M** (~26.9% of total)
- **Pale White** is the most popular colour at **$174.53M**
- **Austin** is the top dealer region with **$31.04M** (Manual) + **$34.00M** (Auto)
- **Toyota** has the highest YTD car sales among all companies
- Strong **YoY growth of 23.59%** in total sales reflects market expansion

---

## 🙋 Author

**Your Name**  
Data Analyst | [LinkedIn](https://linkedin.com/in/yourprofile) | [Tableau Public](https://public.tableau.com/profile/yourprofile)

---

## 📄 License

This project is for educational and portfolio purposes.
