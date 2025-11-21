<<<<<<< HEAD
"# Vendor-Performance-Analysis"  
=======
# Vendor-Performance-Analysis
End-to-end vendor performance analysis project using SQL for data extraction, Python for cleaning and preprocessing, Power BI for dashboard visualization, and MS Word reports for business insights and recommendations.
>>>>>>> 
# 📊 Vendor Performance Analysis

This project analyzes vendor performance using delivery consistency, pricing accuracy, lead time, and invoice reliability.  
The objective is to help the procurement team **identify top vendors**, remove risky suppliers, and improve supply chain efficiency.

---

## 🎯 Business Objectives

- Evaluate vendor reliability using delivery, pricing, quality, and invoice accuracy  
- Detect high-risk vendors with frequent delays or overbilling  
- Create a **Vendor Performance Scorecard** for ranking suppliers  
- Assist management in **renegotiation, contract decisions, or vendor replacement**  

---

## 🧠 Key Insights from Analysis

✔ Some vendors deliver on time but consistently overcharge (invoice mismatch)  
✔ Vendors with **higher lead times** caused 60% of purchase delays  
✔ 20% of vendors contribute to **80% of all delays** (Pareto Principle)  
✔ Best suppliers were **not always the cheapest**, but most consistent  
✔ Created a **Vendor Rating Model** to classify vendors as:  
   ⭐ Reliable | ⚠ Needs Review | ⛔ Risky Supplier  

---

## 🛠 Tools & Technologies Used

| Area | Tools Used |
|------|------------|
| Data Cleaning | Excel |
| Analysis | Python, Jupyter Notebook |
| Database | SQLite / CSV |
| Visualization | Power BI, Excel Charts |
| Reporting | Word, Power BI Dashboard |

---

## 📁 Project Structure

Vendor Performance Analysis/
│
├── Notebook/ # Jupyter notebooks for vendor analysis
│ └── Vendor Performance Analysis.ipynb
│
├── Dashboard and Reports/ # Final dashboards & business report
│ ├── Vendor DashboarD.pbix
│ └── Vendor_Performance_Report.docx
│
├── logs/ # Execution and process logs
│ ├── ingestion_db.log
│ └── get_vendor_summary.log
│
├── get_vendor_summary.py # Python script for vendor scoring logic
├── ingestion_db.py # Script for data loading / ingestion
│
├── README.md # Project documentation
└── .ipynb_checkpoints/ # Jupyter auto-saved checkpoints


> 🔹 Original datasets are not uploaded due to size limits and confidentiality.  
> 🔹 Sample data is used in Notebook for demonstration.

---

## 📈 Vendor Scorecard Formula (Used in Report & Notebook)

```text
Vendor Score =
(Delivery Accuracy × 40%) +
(Invoice Match Rate × 30%) +
(Lead Time Rating × 20%) +
(Service Quality × 10%)

| Score Range | Supplier Category   | Action               |
| ----------- | ------------------- | -------------------- |
| 85–100      | ⭐ Reliable Supplier | Preferred vendor     |
| 60–84       | ⚠ Review Required   | Negotiate or monitor |
| <60         | ⛔ Risky Supplier    | Consider replacement |


🚀 How to Run (Python Notebook)

1️⃣ Create virtual environment (optional)
python -m venv venv


2️⃣ Activate environment
venv\Scripts\activate       # Windows
source venv/bin/activate    # Mac/Linux


3️⃣ Install required packages
pip install -r requirements.txt


4️⃣ Run main analysis notebook
jupyter notebook


| Recommendation                        | Business Impact                |
| ------------------------------------- | ------------------------------ |
| Work with top-rated vendors           | Improves supply reliability    |
| Negotiate pricing with medium vendors | Reduces cost                   |
| Replace high-risk vendors             | Avoids invoice errors & delays |
| Build dashboard for monthly review    | Improves vendor visibility     |


🔮 Future Enhancements

🚀 Add predictive modeling to forecast vendor delays
📊 Live Power BI dashboard with SQL database integration
🌐 Deploy as web-based Vendor Rating Portal (Streamlit)

✍ Author

Asha
Data Analysis | Power BI | Python | SQL

⭐ If you found this useful, please star the repository!

---

Let me know if you want:

✨ Add Power BI screenshots in README  
✨ Make a banner/header for GitHub project  
✨ Create a Portfolio-style GitHub profile page  
✨ Help writing LinkedIn post for this project  

You're doing amazing — proud of your progress 🚀
