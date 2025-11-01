Jordan Used Car Price Analysis 2023
An end-to-end data analysis project, starting with raw, messy data and concluding with an interactive dashboard for analyzing Jordan's used car market.

Tools Used
Python (Pandas): For Data Cleaning & Feature Engineering.

Power BI: For building the interactive dashboard.

The Challenge: Data Cleaning
The raw dataset was extremely messy. I used Python (Pandas) to address the following challenges:

Column Splitting: Transformed a single text column (e.g., "Byd F0 2018") into three separate columns (Brand, Model, and Year).

Text Extraction: Cleaned the engine power column (e.g., "1000 CC" or "1500 CC Turbo") to extract numerical values only.

Category Standardization: Cleaned the transmission column to standardize various entries (e.g., "A/T / AMG Cabrio" and "Automatic") into a single "Automatic" category.

Handling Missing Values: Dropped rows that lacked essential data (like the 'Year').

The Result: Final Dashboard
An interactive dashboard that allows users to filter the car market by brand, year, and transmission type. It displays key performance indicators (KPIs) such as average price and total car count.
<img width="1187" height="549" alt="FinalDashpord" src="https://github.com/user-attachments/assets/6e5b08fb-da8c-4611-8825-eab2ad491578" />
