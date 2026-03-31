About the Project
This is a two-phase end-to-end analytics project built on the Olist Brazilian E-Commerce dataset — one of the most comprehensive multi-relational retail datasets on Kaggle, spanning 8 interlinked CSV files.
Rather than surface-level reporting, this project asks real business questions and answers them with data engineering, SQL, statistical testing, and behavioural analysis —
bridging the gap between raw data and actionable decisions.



## 🔗 Phase 1 — Market Attribution & Customer Intelligence
📓 `marketing-attribution-analysis.ipynb`

| Analysis | Business Problem Solved |
|---|---|
| 💰 Revenue Analysis | Where is revenue coming from, and is it growing? — Tracked total revenue, monthly trends, and top categories |
| 📍 Location Intelligence | Which cities drive the most business? — Mapped revenue by city using geolocation joins |
| 👥 Customer Segmentation | Are all customers equally valuable? — Classified customers into High, Medium, Low value segments |
| 🔁 Retention Analysis | Are customers coming back? — Measured repeat purchase rate and avg days between orders |
| 📊 RFM Modelling | Who are our best customers right now? — Built Recency, Frequency, Monetary table per customer |

🔬 Phase 2 — Statistical & Operational Intelligence
📓 `statistical-analysis.ipynb`

| Analysis | Business Problem Solved |
|---|---|
| 📐 Hypothesis Testing | Is the spending gap between segments real or noise? — T-Test & Mann-Whitney U confirmed statistically significant difference |
| ⭐ Review vs Spending | Do high spenders rate better? — Weak negative correlation found; high spenders are more critical |
| 💬 Sentiment Analysis | What is the emotional tone of our customers? — Negative sentiment customers spend the most |
| 🚚 Delivery Time | How does delivery speed affect satisfaction? — Ratings drop sharply beyond 10 days |
| ⏱️ Delay Analysis | Are we delivering on time? — Early delivery outperforms on-time in customer satisfaction |
| ⚙️ Process Efficiency | Where does the delay actually happen? — Shipping stage is the biggest bottleneck, not approval | 

💡 Key Takeaways

| Insight | Implication |
|---|---|
| High-value customers spend significantly more (statistically proven) | Invest more in retaining top-tier customers |
| Negative sentiment customers spend the most | Premium buyers need premium post-purchase support |
| Satisfaction drops sharply after 10 days delivery | Set 10 days as the maximum acceptable delivery SLA |
| Early delivery beats on-time delivery in satisfaction | Underpromise and overdeliver on estimated dates |
| Shipping stage causes most delays | Focus operational investment on last-mile logistics |

---

## 🛠️ Tech Stack
`Python` `Pandas` `NumPy` `SQLite` `SciPy` `Matplotlib` `Seaborn` `Kaggle`

---

## 🗂️ Structure
```
├── marketing-attribution-analysis.ipynb   # Phase 1
├── statistical-analysis.ipynb             # Phase 2
└── README.md

