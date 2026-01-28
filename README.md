# 🗳️ Election 2024: Loksabha Analytical Pipeline

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python)
![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-yellow?style=for-the-badge&logo=powerbi)
![Data Analysis](https://img.shields.io/badge/Analysis-Exploratory-green?style=for-the-badge&logo=pandas)

## 📌 Project Overview
This project provides a data-driven deep dive into the **2024 Indian General Election results**. By combining Python's computational power with Power BI's interactive capabilities, I transformed raw electoral data into a comprehensive reporting suite that tracks party performance, victory margins, and candidate statistics.



## 🛠️ Tech Stack & Tools
* **Python (Pandas, Matplotlib, Seaborn):** Used for data cleaning, string manipulation of constituency data, and generating statistical distributions.
* **Power BI:** Used for creating an interactive UI, geographic mapping, and high-level KPI tracking.
* **DAX (Data Analysis Expressions):** Utilized for custom measures and calculated columns within the dashboard.

## 📂 Repository Contents
* `Election_Analysis_Notes.pdf`: Documentation of the Python workflow and logic used for data extraction and cleaning.
* `Election-2024_Powerbi_project.pbix`: The interactive dashboard file for visualization.
* `election_results_2024.csv`: The primary dataset containing constituency-wise results.

## 📊 Key Analytical Features

### **1. Python Data Pipeline**
The Python module focuses on deep-dive statistics that are often difficult to visualize in standard BI tools:
* **Trailing Party Analysis:** Specifically analyzed the "Top 10 Trailing Parties" to identify which parties consistently secured second place (e.g., INC, BJP, AIADMK).
* **Victory Margin Insights:** Identified significant outliers, such as the highest victory margin in Indore (Shankar Lalwani).
* **Automated Data Cleaning:** Handled multi-line CSV entries and stripped unnecessary whitespace from candidate and party names.



### **2. Power BI Dashboard**
The interactive dashboard serves as a front-end for non-technical stakeholders:
* **Macro View:** KPI cards showing total seats, leading parties, and average margins.
* **Geographic Insights:** Visualization of seat distribution across different Indian States and Union Territories.
* **Drill-through Capability:** Filter by specific party (e.g., BJP, INC, SP) to see their specific performance metrics instantly.

## 🚀 How to Run
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/election-2024-analysis.git](https://github.com/your-username/election-2024-analysis.git)
    ```
2.  **Run Python Analysis:**
    * Ensure you have the required libraries: `pip install pandas matplotlib seaborn`
    * Run the scripts provided in the project notes to view the margin distribution plots.
3.  **View Dashboard:**
    * Open `Election-2024_Powerbi_project.pbix` in **Power BI Desktop**.

## 📈 Key Insights
* **The "Runner Up" Landscape:** Analysis revealed that the **Indian National Congress** was the leading trailing party in terms of total vote share in seats lost.
* **Performance Outliers:** The project highlights the contrast between extremely high-margin "safe seats" and razor-thin victory margins that decided the final tally.

---
**Author:** IBAD REHMAN 
**Project Type:** Data Science / Business Intelligence Portfolio
