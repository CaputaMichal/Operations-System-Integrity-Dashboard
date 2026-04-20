# Operations System Integrity Dashboard

## 📊 Project Overview
This dashboard was developed to monitor and analyze technical friction within operational and financial processes. It tracks critical issues reported by internal teams, such as **reconciliation discrepancies**, **missing data batches**, and **system interface failures**. 

The goal of this tool is to provide data-driven insights into system reliability, allowing management to identify root causes of operational blockers and optimize resource allocation.

**Data Privacy:** All data has been anonymized and neutralized for portfolio demonstration purposes.

## 🚀 Key Operational Insights
* **System Friction Analysis:** Identifying which software or interface generates the highest volume of errors (e.g., missing batches or data drops).
* **Reconciliation Integrity:** Tracking discrepancies between systems to ensure financial data consistency.
* **Workload Drivers:** Pinpointing the most frequent reasons for ticket creation to target areas for system improvements or team training.
* **Top Impactors:** Highlighting the most active "Super Users" and the company codes most affected by technical glitches.

## ⚙️ Advanced Analytics (DAX Measures)
The report utilizes a dedicated `Measures_table` with advanced DAX logic to provide dynamic insights:
* **Dynamic Rankings:** Implementation of `CompanyCodeRank`, `SU Rank`, and `User Rank` to automatically surface the most critical entities without manual filtering.
* **Contextual Percentages:** `Pct of Tickets` measures calculate the share of specific issues within the current filter context versus the total, ensuring accurate ratio analysis.
* **Performance Tracking:** `AVG resolution time (days)` monitors the efficiency of the technical support in resolving reported system blockers.

## 🛠 Tech Stack
* **Power BI:** Data modeling and interactive visualization.
* **DAX:** Advanced analytical formulas and ranking logic.
* **Power Query:** Data transformation and cleaning of raw operational logs.

## 📈 Dashboard Preview
### 1. Operations Summary
![Summary Preview](preview_summary.png)
*High-level overview of ticket volume, estimated impact value, and Top-N analysis of reasons and users.*

### 2. System & Source Analysis
![Sources Preview](preview_sources.png)
*Deep dive into resolution times by source and monthly activity heatmaps for specific error categories.*

## 📁 Files in Repository
* `FinOps-Technical-Integrity-Dashboard.pbix`: The full interactive Power BI report.
* `README.md`: Project documentation and business context.
