# Multi-Region FinOps & Inventory Optimization Engine

A data-driven financial operations and supply chain analytics pipeline designed to optimize working capital, model inventory dynamics across distributed international warehouses, and compute core FinOps metrics.





## 📌 Project Overview
Managing inventory across cross-border hubs requires balancing customer fulfillment with cash flow constraints. This project analyzes multi-region warehouse operations to balance carrying costs against ordering expenses, automate inventory classification, and calculate working capital metrics.

### Key Financial & Operational Capabilities
* **Economic Order Quantity (EOQ):** Minimizes total holding and order setup costs using operations research optimization.
* **Safety Stock & Buffer Modeling:** Mitigates stockout risk based on lead times and demand variability.
* **ABC Classification (Pareto Analysis):** Categorizes SKUs by cumulative annual usage value to optimize capital allocation.
* **Days Inventory Outstanding (DIO):** Measures working capital velocity and cash-to-cash cycle efficiency.
* **Executive Dashboard Ready:** Outputs structured datasets formatted for Power BI reporting across regional operational zones.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Data Processing & Analytics:** Pandas, NumPy
* **Visualization Layer:** Power BI Desktop
* **Source Dataset:** Supply Chain Data (Kaggle)

---

## 📂 Repository Structure
```text
├── README.md
├── .gitignore
├── finops_inventory_analysis.ipynb
├── data/
│   ├─Other important files like sku_metrics, region_summary, supplier_scorecard
