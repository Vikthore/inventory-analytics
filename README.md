
# 📦 Warehouse Inventory Analytics - Warehouse One

## 🧠 Project Overview

This project provides an in-depth analysis of inventory data for **Warehouse One**, located in Igbo Efun, Lekki. The main objective is to assess inventory health, monitor spatial stock distribution, and recommend actions to minimize spoilage and optimize usage. The dataset includes floor-by-floor breakdowns of item quantities, statuses (Good, Spoiling, Expired), and storage sections.

---

## 🔍 Key Findings

- **Total Inventory Items:** 1,538
- **Top Item Categories by Volume:**
  - Plywood boards: 150 units
  - Drinking cups: 130 cartons
  - Cupboards and foam chair tops: High-volume, high-risk items
- **Condition Breakdown:**
  - Good: 61.9%
  - Spoiling: 25.9%
  - Expired: 12.2%
- **Top Floors by Stock Concentration:**
  - Ground floor has the highest inventory load
  - Second and Top floors follow in stock levels
  - Containers contribute marginally to overall volume

---

## 📈 Insights & Recommendations

1. **Spoilage & Expiry Mitigation:** Over 38% of stock is deteriorating. Immediate intervention is required through condition-based alerting and reallocation.
2. **Stock Redistribution:** Overstocked Ground floor items should be redistributed or subjected to FIFO (First In, First Out) protocols.
3. **Condition Segmentation:** Conduct targeted audits on Spoiling and Expired segments to isolate causes like ventilation, moisture, or improper stacking.
4. **High-Risk Items:** Products such as Echolacs, Cupboards, Mannequins, and Generators have a high tendency to degrade. Storage conditions must be reassessed.
5. **Storage Environment Controls:** Establish environmental standards per room/section — e.g., airflow, humidity control, and protective enclosures.
6. **Digital Monitoring:** Propose integration with a digital inventory system featuring:
   - Real-time updates
   - Expiry prediction modeling
   - Automated status notifications

---

## ⚙️ Tools & Technologies

- **Data Processing:** Python (Pandas, NumPy)
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Reporting:** Streamlit (optional), Excel-based dashboards

---

## 🗂️ File Structure

```
Warehouse-Analytics/
├── warehouse_data.csv
├── inventory_analysis.py
├── visualization_report.ipynb
├── floor_item_status_chart.png
├── README.md
```

---

## 👤 Contributor

**Victor Ikechukwu**  
Inventory Systems Analyst & Data Enthusiast  
📧 Email: vikechukwu@gmail.com  
🌍 Location: Lagos, Nigeria  
🔗 [GitHub Profile](https://github.com/Vikthore)

---

