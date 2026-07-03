# 🚢 Teleport Intelligence Dashboard

A Python-powered analytics dashboard for cargo shortfall 
prediction and revenue optimisation.

Built by a commercial product owner learning data science 
— applied directly to real logistics operations.

---

## 🎯 Business Problem

Teleport Guaranteed (TG) contracts commit customers to a 
minimum cargo tonnage per flight. When customers fall short, 
shortfall fees apply — but by then, revenue is already lost.

This dashboard answers three questions:
- Where is revenue leaking right now?
- Which contracts will shortfall before it happens?
- Which routes should we prioritise for recovery?

---

## 🔧 What It Does

| Feature | Status |
|---|---|
| Shortfall fee calculator | ✅ Done |
| Contract risk flagging (On Track / At Risk / Shortfall) | ✅ Done |
| Revenue leakage analysis by route | 🔨 In Progress |
| Shortfall risk ML prediction model | 📅 Coming |
| Route tonnage forecasting (time series) | 📅 Coming |
| Customer segmentation | 📅 Coming |
| Streamlit web dashboard | 📅 Coming |

---

teleport-intelligence-dashboard/
├── notebook.ipynb       ← main Colab notebook
├── data/
│   └── teleport_cargo_data.csv   ← simulated dataset
├── outputs/
│   └── shortfall_by_route.png    ← sample chart
└── README.md

---

## 🛠️ Tools Used
Python · Pandas · NumPy · Matplotlib · Scikit-learn · Google Colab

---

## 📊 Dataset
Simulated cargo dataset — 1,296 records · 10 routes · 
10 customers · 26 weeks (6 months)

*Note: All data is simulated. No real Teleport data is used.*

---

## 👤 Author
**Alyaa Mazelan** — Assistant Manager & Commercial Product Owner  
Building toward: Head of Product @ a data-driven logistics company  
GitHub: github.com/alyaamazelan

## 📁 Project Structure
