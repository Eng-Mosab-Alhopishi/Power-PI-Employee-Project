# 📊 HR Analytics Dashboard: From Data to Decisions

![Project Status](https://img.shields.io/badge/status-completed-green?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Analytics-2D72B8?style=for-the-badge&logo=tableau&logoColor=white)
![ETL](https://img.shields.io/badge/ETL-Power%20Query-8A2BE2?style=for-the-badge&logo=microsoft&logoColor=white)

---

## 🌟 Project Overview

This repository hosts an end-to-end **Human Resources Analytics Dashboard**, a powerful business intelligence tool developed in **Microsoft Power BI**. The project's core objective is to transform raw, complex employee datasets into an interactive, intuitive, and visually compelling dashboard. This solution empowers HR departments and executive leadership to move beyond guesswork, enabling them to make critical, data-driven decisions regarding talent management, compensation, and organizational structure.

The dashboard provides a 360-degree view of the company's workforce, uncovering actionable insights from key metrics and trends.

---

## ✨ Live Dashboard Preview

Below is a snapshot of the main dashboard interface. *The best experience is interactive; see the "How to Use" section to explore the full `.pbix` file.*


https://github.com/Eng-Mosab-Alhopishi/Power-PI-Employee-Project/blob/main/Screenshot%202025-09-25%20145218.png

---

## 🎯 Key Features & Strategic Insights

This dashboard is engineered to provide answers to the most pressing HR questions at a glance:

#### Key Performance Indicators (KPIs)
-   **Total Headcount:** A real-time count of the active workforce.
-   **Average Annual Salary:** A crucial metric for budget and compensation analysis.
-   **Average Employee Age:** An indicator of workforce demographics and succession planning needs.

#### Visualizations & Deep Dives
-   **📈 Departmental Headcount Analysis:** A clear breakdown of employee distribution across departments, instantly highlighting the largest and leanest teams.
-   **💰 Compensation Structure Insights:** An in-depth analysis of average salaries by `Job Title`, essential for ensuring fair and competitive pay scales.
-   **📅 Hiring Trends Over Time:** A dynamic line chart that maps employee hires by year, visualizing the company's growth trajectory and key expansion periods.
-   **🌍 Geographic Distribution:** A map visualization showing employee presence by city, critical for location-based resource planning.
-   **📊 Age & Gender Demographics:** Visual breakdowns of the workforce by gender and age groups, providing a clear picture of diversity and inclusion metrics.

---

## 🛠️ The ETL Powerhouse: Data Transformation with Power Query

The foundation of any great dashboard is pristine data. The raw dataset was subjected to a rigorous ETL (Extract, Transform, Load) process within the **Power Query Editor** to ensure absolute data integrity and usability.

#### The Transformation Pipeline:
1.  **Schema Correction:** Assigned precise data types (`Date`, `Fixed Decimal`, `Whole Number`, `%`) to all columns, enabling accurate calculations and time-intelligence functions.
2.  **Data Cleansing:** Proactively removed blank rows and eliminated duplicate records based on the unique `Employee ID` to prevent data skew.
3.  **Text & String Manipulation:** Split `Full Name` into `First Name` and `Last Name` for granular analysis and applied formatting standards (e.g., `UPPERCASE` for categorical data).
4.  **Feature Engineering:**
    -   **Created Age Groups (Bins):** Grouped employees into logical 10-year age brackets, transforming a continuous variable into a categorical one for powerful demographic analysis.
    -   **Extracted Time Intelligence Data:** Utilized the `Hire Date` to build a robust date table for trend analysis over years, quarters, and months.
5.  **Structural Modifications:** Strategically removed irrelevant columns (`Exit Date`) to streamline the data model and focus the analysis on the current workforce.

---

## 💻 Tech Stack

-   **Primary Tool:** **Microsoft Power BI Desktop**
-   **Data Transformation:** **Power Query (M Language)**
-   **Data Modeling & Calculations:** **DAX (Data Analysis Expressions)**

---

## 🚀 Getting Started

Ready to explore the data?

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    ```
2.  **Download the `.pbix` file.**
3.  **Open the file in Power BI Desktop.**
4.  **Interact with the visuals!** Click, drill down, and filter to uncover your own insights.

---

## 🤝 Let's Connect!

I'm passionate about leveraging data to tell stories and drive business decisions. If you have any questions, feedback, or just want to connect, feel free to reach out!

-   **LinkedIn:** [linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)
-   **GitHub:** [github.com/your-username](https://github.com/your-username)
