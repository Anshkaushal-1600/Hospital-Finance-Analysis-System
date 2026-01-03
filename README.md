# Hospital-Finance-Analysis-System
A browser-based Hospital Financial Analysis System (HFAS) that links clinical operations (ALOS, CMI) to financial statements. Features scenario planning, Excel ingestion, and automated board reporting.
# 🏥 HFAS: Hospital Financial Analysis System

> An integrated financial planning & analysis (FP&A) platform designed specifically for the Healthcare sector.

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Stack](https://img.shields.io/badge/tech-JavaScript%20%7C%20Tailwind%20%7C%20Chart.js-teal)

## 💡 Overview
HFAS is a specialized financial modeling engine that bridges the gap between **Clinical Operations** and **Financial Performance**. Unlike generic financial models, HFAS calculates revenue and expenses based on healthcare-specific drivers like Average Length of Stay (ALOS), Case Mix Index (CMI), and Licensed Bed Capacity.

It allows administrators to upload raw financial data, run "What-If" pandemic/growth scenarios, and generate automated PDF board reports.

## 🚀 Key Features

*   **🏥 Clinical-to-Financial Linkage:** Revenue is not just a hardcoded number; it is derived from *Admissions × Base Rate × Acuity (CMI)*.
*   **🎛️ Real-Time Simulation:** Interactive sliders to adjust ALOS, Collection Rates, and Supply Inflation to see immediate impacts on Operating Margin.
*   **📊 3-Statement Integration:** Changes in patient volume automatically flow through the P&L, Balance Sheet, and Cash Flow Statement.
*   **📥 Data Ingestion Engine:** Parses raw `.xlsx` hospital financial statements and visualizes actuals vs. budget.
*   **🚨 Automated Alerts:** Algorithmic detection of risks such as "Capacity Strain" (>85% Occupancy) or "Liquidity Risk" (<60 Days Cash on Hand).
*   **📄 Executive Reporting:** One-click generation of PDF Board Reports with KPI summaries and analyst commentary.

## 🛠️ Tech Stack

*   **Frontend:** HTML5, Tailwind CSS (Responsive Medical Dashboard)
*   **Logic:** Vanilla JavaScript (ES6+)
*   **Data Parsing:** SheetJS (Excel/CSV ingestion)
*   **Visualization:** Chart.js
*   **Reporting:** jsPDF

## 🩺 Logic & KPIs Implemented

The system monitors critical healthcare metrics:
*   **Occupancy Rate:** Ensures patient volume aligns with licensed bed capacity.
*   **Operating Margin:** Net Patient Revenue minus Total Operating Expenses.
*   **Days Cash on Hand (DCOH):** A critical liquidity measure for non-profit and for-profit hospitals.
*   **ALOS Efficiency:** Visualizes the cost impact of extended patient stays.



## 🚀 Getting Started

1.  Clone the repo:
    ```bash
    git clone https://github.com/yourusername/hfas-clinical-finance.git
    ```
2.  Open `index.html` in any browser.
3.  Select **"Pandemic Stress Test"** from the scenario dropdown to see the model in action.

## 🤝 Contributing
Open to contributions regarding DRG reimbursement logic and staffing model improvements.

---
*Built by Ansh kaushal
for Healthcare 
