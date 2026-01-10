# 📈 Practice Sessions - Global Data Science Job Market & Salary Analytics

🌟 Project Overview
-------------------

This project provides a deep-dive analysis of the Data Science job market using **Power BI**. The dashboard transforms complex workforce data into interactive visual stories, helping stakeholders understand compensation benchmarks, geographic demand, and the evolving requirements for roles like Data Engineers, Scientists, and Analysts.

<p align="center">
    <img src="https://github.com/dyneth02/PowerBI-Practice-Chores/blob/main/screenshots/Screenshot%202026-01-10%20001222.png">
</p>

<p align="center">
    <img src="https://github.com/dyneth02/PowerBI-Practice-Chores/blob/main/screenshots/Screenshot%202026-01-10%20001236.png">
</p>

<p align="center">
    <img src="https://github.com/dyneth02/PowerBI-Practice-Chores/blob/main/screenshots/Screenshot%202026-01-10%20001249.png">
</p>

<p align="center">
    <img src="https://github.com/dyneth02/PowerBI-Practice-Chores/blob/main/screenshots/Screenshot%202026-01-10%20001302.png">
</p>

<p align="center">
    <img src="https://github.com/dyneth02/PowerBI-Practice-Chores/blob/main/screenshots/Screenshot%202026-01-10%20001321.png">
</p>

<p align="center">
    <img src="https://github.com/dyneth02/PowerBI-Practice-Chores/blob/main/screenshots/Screenshot%202026-01-10%20001333.png">
</p>

<p align="center">
    <img src="https://github.com/dyneth02/PowerBI-Practice-Chores/blob/main/screenshots/Screenshot%202026-01-10%20001346.png">
</p>

<p align="center">
    <img src="https://github.com/dyneth02/PowerBI-Practice-Chores/blob/main/screenshots/Screenshot%202026-01-10%20001356.png">
</p>

🚀 Key Insights & Features
--------------------------

-   **Highest Paying Roles:** Identified **Senior Data Scientist** ($156K) and **Machine Learning Engineer** ($155K) as the leading roles in median yearly salary.
-   **Salary vs. Degree Analysis:** Uncovered that **93.30% of Data Scientist** postings require a degree, whereas **Data Engineering** shows a higher flexibility with **52.59%** of postings not mentioning a degree requirement.
-   **Global Compensation Trends:** Comparison of median salaries across the UK, USA, France, and India, highlighting a peak median of over **$0.2M in France** for specific senior roles.
-   **Hiring Funnel Metrics:** A detailed funnel analysis showing a **2.4% final hire rate** from an initial pool of 5.0K job posting views.
-   **Work-from-Home Dynamics:** Visualized that **13.15%** of global postings explicitly offer remote work options.

🛠️ Tech Stack & Tools
----------------------

-   **Tool:** Power BI Desktop
-   **Data Processing:** Power Query (M Language) for ETL and data cleaning.
-   **Calculations:** Advanced **DAX (Data Analysis Expressions)** for calculated columns, measures, and time-intelligence.
-   **Visuals:** * **Sankey Diagrams** for quarterly salary shifts.
    -   **Waterfall Charts** for compensation breakdown (Base, Benefits, Stocks).
    -   **Geospatial Maps** for degree-requirement distribution.
    -   **Funnel Charts** for recruitment pipeline tracking.

📊 Dashboard Breakdown
----------------------

### 1\. Salary Benchmarking

An interactive comparison of Yearly vs. Hourly pay. It features a dual-axis chart showing that while Senior Data Scientists lead in yearly pay, **Machine Learning Engineers** often command higher hourly rates ($60.75/hr).

### 2\. Market Trends (2024)

A time-series analysis tracking job counts and salary fluctuations throughout the year.

-   **Average Job Count:** 39.908K.
-   **Trend:** A noticeable peak in Job Counts around March/April followed by a strategic consolidation toward the end of the year.

### 3\. Hiring & Funnel Analytics

Visualizes the journey from "Viewed" to "Hired." This section is crucial for HR professionals to identify bottlenecks in the application process where candidates drop off most frequently (between "Submitted" and "Interviewed").

🧪 Advanced DAX Examples Used
-----------------------------

To provide deeper insights, the following logic was implemented:

-   **Median Salary Calculation:** Dynamic filtering based on job titles and country.
-   **Year-over-Year (YoY) Growth:** Tracking how salary trends shifted between quarters in 2024.
-   **Goal Tracking:** A gauge visual showing a median salary of **$113K** against a target goal of **$121K**.

📁 Repository Structure
-----------------------

-   `Dashboards/`: Contains exported PDF/Image versions of the report.
-   `Data/`: (Optional) Sample datasets or schemas used for the analysis.
-   `Source_File.pbix`: The core Power BI project file.
