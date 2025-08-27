Note: To access the files, download “Counselling Budget Tracker_Residential Services.xlsx.”
For a step-by-step walkthrough, download “Step-by-Step Guide_Counselling Budget Tracker – Residential Services Practical Solution.pdf.”

# Counselling-Budget-Tracker-Portfolio
Excel-based budget tracking tool for residential services counselling, built as a Program Assistant.

This Excel spreadsheet, titled "Counselling Budget Tracker_Residential Services.xlsx," is a custom-built tool I developed as a Program Assistant for the Residential Services team. It serves as an efficient system to monitor and manage counselling budgets for multiple individuals, ensuring transparency, automation, and proactive alerts for budget constraints. The tracker was designed to handle variable session data while providing real-time summaries and visualizations, making it a practical example of my skills in Excel automation, data organization, formula implementation (e.g., VLOOKUP, SUMIF), pivot tables, and dashboard creation

Key features include:

Data Entry and Tracking: A dedicated sheet for logging sessions with automatic calculations for running totals and remaining budgets.
Reference Lists: A simple lookup sheet for names and initial budgets to enable dropdown selections and easy scalability.
Visualizations: Pivot table-based charts for quick budget overviews.
Dashboard: A summary view with status alerts to flag low budgets.

This project demonstrates my ability to create user-friendly, data-driven tools that support operational efficiency in a service-oriented environment like residential counselling. It uses Excel's built-in functions to minimize manual work and reduce errors, while incorporating conditional logic for decision-making support.

Project Summary
The spreadsheet tracks counselling budgets for four individuals in the Residential Services program: Ayodele ($3,000 initial budget), Katie ($1,550), Michelle ($6,500), and Tharangi ($2,700). Each person's data includes their name, initial budget, session dates, session amounts (fixed at $160 per session), spent amounts, running total spent, and remaining budget. The tool assumes sessions are entered chronologically and uses formulas to auto-update totals as new data is added.

From the provided data (as of the current date, August 27, 2025):
Sessions logged include early July 2025 dates: Ayodele on July 1, Katie on July 2, Michelle on July 3, and Tharangi on July 4. However, the full dataset implies additional sessions (abbreviated with "..." in the document), leading to higher spent amounts for some.

Total initial budgets across all individuals: $13,750.
Total spent to date: $3,380.
Total remaining: $10,370.

The spreadsheet is structured across four sheets:
Counselling Budgets: Main data entry sheet with columns for Person's Name, Initial Budget (pulled via VLOOKUP), Session Date, Session Amount ($160), Spent This Session, Running Total Spent (using SUMIF for cumulative sums per person), and Remaining Budget (Initial minus Running Total).
Lists: Reference sheet listing names and initial budgets for data validation and lookups.
Budget Visual Chart: Pivot table summary showing aggregated data per person (e.g., Sum of Remaining Budget, Initial Budget, and Total Spent). It includes grand totals and can be used to generate charts like bar graphs for visual comparison of budgets vs. spending.
Counselling Summary Dashboard: High-level overview with VLOOKUP for initial budgets, SUMIF for total spent, calculated remaining budgets, and a Status column (e.g., "URGENT: ACTION REQUIRED!" if remaining < $500, otherwise "OK"). This acts as a quick-reference panel for managers.

This setup ensures the tracker is dynamic—adding a new session row automatically updates all related calculations, summaries, and visuals without manual intervention.

Insights from the Excel Sheet and Visualization Dashboard
Based on the data in the sheets, here are key insights derived from the formulas, summaries, and dashboard:

Individual Budget Status:

Ayodele: Initial $3,000; Spent $2,900 (implying approximately 18 sessions at $160 each); Remaining $100. Status: "URGENT: ACTION REQUIRED!" – This highlights a critical need for budget replenishment or session limits, as the remaining amount is below a typical $500 threshold.
Katie: Initial $1,550; Spent $160 (1 session); Remaining $1,390. Status: "OK" – Budget is largely intact, with room for about 8-9 more sessions.
Michelle: Initial $6,500; Spent $160 (1 session); Remaining $6,340. Status: "OK" – Highest budget, minimally used so far, allowing for extensive future sessions (around 39 more).
Tharangi: Initial $2,700; Spent $160 (1 session); Remaining $2,540. Status: "OK" – Healthy remaining balance, supporting about 15 additional sessions.


Overall Trends from the Budget Visual Chart:

The pivot table shows a grand total spent of $3,380 (about 25% of the initial $13,750), with $10,370 remaining. This indicates the program is in its early stages of utilization, but Ayodele's high spending (86% of budget used) skews the totals and signals potential uneven distribution of counselling needs.
Visualization potential: A stacked bar chart could illustrate Initial Budget (full bar) broken into Spent (red segment) and Remaining (green segment) per person, making it easy to spot imbalances. For example, Ayodele's bar would be mostly red, while others are predominantly green.


Dashboard Highlights:

The summary uses conditional formulas to flag issues, promoting proactive management. Currently, only Ayodele requires urgent action, which could involve reallocating funds from underutilized budgets (e.g., Michelle's).
Efficiency Insight: With automated sums and lookups, the tool reduces administrative time. If expanded, it could track session trends over time (e.g., monthly spending via additional pivot filters).



These insights showcase how the spreadsheet not only tracks data but also supports informed decision-making, such as prioritizing budget reviews for high-spenders.
