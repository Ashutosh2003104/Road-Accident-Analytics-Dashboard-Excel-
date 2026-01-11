
---

# Road Accident Analytics Dashboard (Excel)

An interactive, stakeholder-driven dashboard developed to analyze **3.07 million records** of road accident data (2021–2022). This project provides a data-driven approach to identifying safety trends and high-risk areas to assist government departments in policy making.
<img width="1465" height="672" alt="image" src="https://github.com/user-attachments/assets/28edf950-0694-4376-a3b3-e83fc2b8244c" />


##  Project Overview
The goal of this project was to transform raw, unstructured accident data into a dynamic visualization tool for key stakeholders such as the **Ministry of Transport**, **Police Force**, and **Emergency Services**. The dashboard enables granular filtering and year-over-year (YoY) comparison to monitor road safety KPIs.

##  Key Features & KPIs
*   **Primary KPIs:** Total casualties after accidents, segmented by severity (Fatal, Serious, Slight).
*   **Vehicle Analysis:** Casualties categorized by vehicle type (Cars, Vans, Bikes, etc.) with custom grouped categories.
*   **Trend Tracking:** Monthly comparison of current year (CY) vs. previous year (PY) casualties.
*   **Road Distribution:** Casualties segmented by Road Type (Single/Dual Carriageway, Roundabout) and Road Surface conditions (Dry, Wet, Snowy).
*   **Environmental Factors:** Relation between casualties by Area (Urban vs. Rural) and Light Conditions (Daylight vs. Dark).
*   **Interactive Filters:** Slicers for Area type and a Timeline filter for specific Years, Quarters, and Months.

##  Technical Skills Demonstrated
*   **Data Cleaning:** Used "Find and Replace" and filtering to correct typo errors (e.g., "Fetal" to "Fatal") and handle missing values across 3.07M rows.
*   **Advanced Data Processing:** Developed custom columns using the `TEXT` function to extract Months and Years from raw date fields.
*   **Pivot Tables & Modeling:** Generated complex Pivot Tables to aggregate data across 21 different fields.
*   **Advanced Formulas:** Utilized `GETPIVOTDATA` to create dynamic KPI cards and percentage calculations that update automatically based on filters.
*   **Dynamic Visualizations:**
    *   Donut Charts for Severity distribution.
    *   Combo Charts for Monthly Trend Analysis.
    *   Treemaps for Road Surface conditions.
    *   Bar Charts for Road Type analysis.
*   **UX/UI Design:** Integrated Slicers, Timelines, and Hyperlinks for seamless navigation between the Dashboard and Data Analysis sheets.

##  Dataset Metadata
*   **File Extension:** `.xlsx`
*   **Total Records:** 3.07 Million
*   **Total Fields:** 21
*   **Time Period:** 2021 - 2022
*   **Source:** Demo data (similar to Kaggle Road Accident Datasets)

##  Step-by-Step Implementation
1.  **Requirement Gathering:** Defined KPIs based on stakeholder needs (e.g., Ministry of Transport).
2.  **Data Cleaning:** Standardized categorical data and removed inconsistencies.
3.  **Data Processing:** Created calculated fields for time-based analysis.
4.  **Data Analysis:** Built multiple Pivot Tables on a dedicated "KPI" sheet.
5.  **Visualization:** Designed and formatted charts to match a professional dark-themed UI.
6.  **Interactivity:** Linked Slicers and Timelines to all relevant Pivot Tables using "Report Connections."

##  Insights
*   **Highest Casualties:** Analysis shows that Cars are involved in the vast majority of casualties compared to other vehicle types.
*   **Area Impact:** Rural areas often show different severity patterns compared to Urban centers, requiring different safety intervention strategies.
*   **Surface Safety:** Dry road conditions surprisingly account for a high volume of incidents, suggesting driver behavior or speed may be a factor alongside weather.

---

### How to use
1. Download the `Road Accident Analyzer.xlsx` file.
2. Open in Microsoft Excel (2019 or later recommended).
3. Use the **Filter Panel** on the right to toggle between Urban and Rural data.
4. Use the **Timeline** to see how safety trends evolved month-to-month.
