# 💹 FinSight — Finance Analytics Dashboard (Power BI)

An interactive Power BI dashboard built to help financial organizations monitor and analyze transactions, customer behavior, fees, taxes, and performance across business segments and regions — in real time.

![Overview Analysis](screenshots/overview_analysis.png)

---

## 📌 Business Problem

Management teams at a financial organization needed a centralized way to track:

- Overall transaction growth and financial performance
- Monthly trends in transaction amounts
- Successful vs. failed vs. pending transactions
- Customer segment contribution
- State-wise financial performance
- Transaction type profitability
- Gender-based customer analysis
- Year-over-Year (YoY) performance changes

Previously this data was scattered and hard to analyze at a glance — this dashboard consolidates it into one interactive view.

## 🎯 Objective

Provide a centralized analytical solution that helps stakeholders:

- Monitor KPIs in real time
- Identify high-performing customer segments and states
- Analyze transaction patterns and trends
- Track operational fees and taxes
- Understand customer demographics
- Improve financial decision-making and business strategy

## 🛠️ Tools & Tech Stack

- **Power BI Desktop** — data modeling, DAX, visualization
- **Power Query** — data cleaning & transformation
- **DAX** — calculated KPIs and dynamic measures

## 📊 Dashboard Features

### Page 1 — Overview Analysis

| KPI | Description |
|---|---|
| Total Amount | Total transaction amount processed, with YoY growth |
| Total Transactions | Total number of transactions, with yearly volume trend |
| Avg Transaction Value | Average amount per transaction |
| Total Fees | Total fees collected across all transactions |
| Total Tax | Total tax generated from all transactions |

**Charts:**
- **Total Amount by Month** — Line/Area chart to spot seasonal trends and spikes
- **Total Amount by Transaction Status** — Donut chart (Success / Failed / Pending) to measure operational efficiency
- **Total Amount by Customer Segment** — Horizontal bar chart across Retail, Premium, SME, Corporate, Wealth
- **Total Amount by State** — Horizontal bar chart comparing top-performing regions
- **Transaction Type Analysis** — Matrix table (Amount, Fees, Tax, Transaction Count) across 10 transaction types: Bill Payment, Card Payment, Deposit, Fee Charge, Interest Credit, Investment, Loan EMI, Refund, Transfer, Withdrawal
- **Total Amount by Gender** — Donut chart comparing Male vs. Female contribution

**Interactive Filters:** Year, Dynamic Measure, Occupation, Category

![Transactions Drill-through View](https://github.com/Sanketgaikwad20/Finance-Analysis-Dashboard/blob/main/Snapshot%20of%20Transaction%20Dashboard%20.png)

### Page 2 — Transactions (Drill-through)

A detailed, filterable grid view of every underlying transaction record — including transaction ID, customer name, date, type, status, gender, segment, state, amount, fees, and tax — for granular, record-level analysis.

## 💡 Key Insights Delivered

- Real-time visibility into ₹135M+ in total transaction volume across 15K+ transactions
- Instant identification of top-contributing customer segments (Retail leads at ₹74M) and states (Maharashtra leads at ₹20M)
- Clear view of transaction success rate to flag operational issues early
- Profitability breakdown by transaction type to guide fee/tax strategy

## 🚀 Skills Demonstrated

- Business requirement analysis and translation into technical specs
- Data modeling and DAX measure creation
- Dynamic/what-if measure switching
- Dashboard UX design (KPI cards, drill-through pages, slicers)
- Storytelling with data for business stakeholders

## 📁 Repository Contents

```
├── FinSight_Dashboard.pbix       # Power BI project file
├── Business_Requirements.docx   # Original business requirements doc
├── screenshots/
│   ├── overview_analysis.png
│   └── transactions_view.png
└── README.md
```

## 📬 Contact

Feel free to connect or reach out if you'd like to discuss the project or explore collaboration opportunities!
