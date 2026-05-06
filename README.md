☕ South African Cafe Sales Analysis (Portfolio Project)

A full-cycle data analysis project focused on cleaning and transforming "dirty" cafe sales data into actionable business insights using Excel and Power Query.

📊 Phase 1: Data Cleaning & Transformation (COMPLETED)
In this phase, I handled real-world "dirty" data to ensure accuracy for a local South African business.

🧹 Cleaning Steps Taken:
Item Standardisation: Fixed "ERROR" and "UNKNOWN" values in the Item column and used Capitalise Each Word for a professional look.

Financial Audit: Identified that the original "Total Spent" column had logical errors. I created a new Total Sales column using the formula [Quantity] * [Price Per Unit] to ensure 100% accuracy.

Handling Missing Data: Replaced empty cells and null values with "Unknown" (for text) and "0" (for numbers) to prevent math errors.
Localization (ZAR): Converted all monetary values to South African Rand (R).

Date Formatting: Resolved American (MDY) vs. South African (DMY) date conflicts to ensure correct time-series analysis.

SA Business Insights (Phase 2 - In Progress)I am currently using Pivot Tables to answer the following:

Top Products: Which items generate the most Rands (R)?

Location Performance: Which South African branch is the top performer?

Sales Trends: Which day of the week is busiest for the cafe?

🛠️ Tools Used Power Query: For Extract, Transform, and Load (ETL) processes.

Excel: For financial calculations and localization.

GitHub: For project documentation and version control.
