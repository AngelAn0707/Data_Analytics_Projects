Project: Mobile Game User Activity Analysis in Tableau Public
Project Description:

Brief project introduction.
This project involved developing an interactive dashboard in Tableau Public for analyzing user activity in a mobile game. The project's goal is to investigate key engagement metrics such as unique users, "Battle Pass" related activity, average time in game, and player age groups, as well as to provide interactive filters for in-depth analysis.

Project Tasks (what you did):

Tasks:
Calculated Fields Creation: Calculated and displayed: Total number of unique game users. Percentage of users active in "Battle Pass" (monthly). Average time spent in the game per unique player (monthly). Time formatting to "HH:MM" for readability. Age groups created with a 5-year increment.
Visualization Creation on Separate Sheets:
Sheet 1: Overall Activity and Battle Pass
Chart with monthly breakdown: Total unique audience and Battle Pass engagement percentage.
Sheet 2: Average Time in Game
Chart with monthly breakdown: Average time in game per unique player.
Text label with formatted time in "HH:MM".
Sheet 3: Heatmap of Time in Game by Age and Quarter
Heatmap: Average time in game by age groups (5-year increment) and activity quarters.
Interactive Dashboard Creation: Combined all three sheets onto a single dashboard. Added filters: "Activity Date," "Age Group," "Game Name" (from game_activity_name), "User Device Language."
Tools and Technologies Used:

Used Tools:
Tableau Public: For data visualization, calculated field creation, and dashboard development.
Microsoft Excel/CSV: Source data file for user activity.

  ![image](https://github.com/user-attachments/assets/e6748e22-779d-45a2-9573-65c53d48244a)

  
Project: Superstore Sales Analysis in Tableau Public
Project Description
This project involved analyzing Superstore sales data in Tableau Public. The project focused on studying the efficiency of delivery and order distribution across various parameters, such as shipping mode, delivery time in days, and geographical location (US states).

Tasks:
Calculate Average Delivery Time: Determined the average number of days taken to deliver each order, based on the Order Date and Ship Date fields.
Create Visualization Sheets:
Sheet 1: Average Delivery Days by Ship Mode
Visualization of the average number of days for delivery for each Ship Mode (Standard Class, First Class, etc.).
Sheet 2: Order Distribution by Delivery Days
Visualization of the number of orders grouped by the number of days taken for their delivery (e.g., 0 days, 1 day, 2 days, etc.).
Sheet 3: Map of Average Delivery Days by State
Geographical map of the USA, displaying the average number of days for delivery for each state using a color gradient.
Assemble Dashboard:
All three sheets were combined into one interactive dashboard.
Add Filters:
Filters for Order Date, Segment, and Ship Mode were included for dynamic data analysis.
Tools Used:
Tableau Public: Primary tool for data analysis and visualization.
Superstore Sales: Standard demonstration dataset in Tableau.

![image](https://github.com/user-attachments/assets/46f49704-4a32-4934-8927-c2231f8f393a)


Project: Product Company Revenue Analysis in Tableau Public
Project Description:
In this project, an interactive dashboard was developed in Tableau Public for analyzing the revenue of a product company. The project expands on a previous dashboard (from Homework Assignment 2) and focuses on calculating and visualizing new metrics such as New MRR (revenue from new users), change in total revenue, and cohort analysis.

Tasks:
Creation of Calculated Fields: Calculated and displayed:
New MRR: Sum of revenue received from new users in their first payment month.
Change in Total Revenue (in %): Percentage change in total revenue relative to the previous month.
Creation of Visualizations on Separate Sheets:
Sheet 1: New MRR
Visualization of New MRR by month.
Sheet 2: Total Revenue and % Change
Dual-axis chart: Total Revenue (absolute value) and percentage change in Total Revenue (relative to the previous month).
Sheet 3: Revenue Cohort Analysis
Table (cohort analysis): Revenue from users, grouped by their first payment month and month after first payment. A gradient was used to display the ratio of revenue in the corresponding month to revenue in the cohort's first month.
Dashboard Expansion: Added new sheets (New MRR, Total Revenue, and cohort analysis) to the dashboard created in Homework Assignment 2. Used filters by location and date for interactive data exploration.
Used Tools:
Tableau Public: For data visualization, calculated field creation, and dashboard development.
Product Company Revenue Data: (The original text had an incomplete phrase here; I've ended it cleanly).

 ![image](https://github.com/user-attachments/assets/00e3175c-8f4f-4d81-9cce-6471068b5a3d)
  
Project: User Conversion Funnel Analysis in Tableau Public
Project Description
This project involved developing an interactive dashboard in Tableau Public to analyze the user journey from registration to first payment. The project focuses on visualizing key conversion funnel stages, calculating conversion rates, and displaying the dynamics of user transitions between steps. Special attention was paid to advanced Tableau features, such as creating new chart types, using tooltips to display metrics, and implementing interactivity with Actions and Parameters.

Tasks:
Creation of Key Numeric Blocks:

Three separate numeric blocks were displayed:
Total number of registered users.
Number of users who started a trial period.
Number of users who made a payment.
Additionally: Conversion Rate (conversion rate from registration to the corresponding step) was displayed in tooltips for the "Trial Period" and "Payment" blocks.
Building a Chart for Registration Dynamics and Trial Conversion:

A chart showing the monthly number of user registrations.
A chart displaying the monthly conversion rate from registered users who transitioned to a trial (regardless of the trial start month).
Development of a Funnel Chart:

A visualization of the conversion funnel, reflecting users' progression through steps from registration to payment.
The chart includes both absolute numbers (number of users completing each step) and relative metrics (conversion rate between steps).
Bonus Task: Interactivity with Actions and Parameters:

Chart of Average Duration to Step: Created a chart displaying the average number of days from registration to payment for each registration month.
Dynamic Update: Configured an action that, upon selecting any step on the funnel chart, re-renders the average duration chart to display the number of days from registration to the selected step.
Tools Used:
Tableau Public: Primary tool for data analysis, creating calculated fields, parameters, actions, and visualizations.
CSV/Excel file: Source data on user step progression (file specified in the task).
Key Calculated Fields (logic examples):
Conversion Rate: COUNTD([User ID (users at step)]) / COUNTD(IF [Step Name] = 'Registration' THEN [User ID] END)
Days to Step: DATEDIFF('day', [Registration Date], [Selected Step Date]) (logic for the bonus task with a parameter).

 ![image](https://github.com/user-attachments/assets/1ed93b1a-be24-475b-a219-2b0b0a32d07f)


Project: Product Company Revenue Analysis in Tableau Public
Project Description
Performed: Revenue analysis, LOD (Level of Detail expressions), Table Calculations, MRR (Monthly Recurring Revenue), cohorts.

Tasks:
Creation of Calculated Fields: (New MRR, % change in Total Revenue)
Creation of Visualizations on Separate Sheets:
Sheet 1: New MRR
Sheet 2: Total Revenue and % Change
Sheet 3: Revenue Cohort Analysis
Dashboard Expansion: (Use of filters by location and date)
Tools Used:
Tableau Public
Product Company Revenue Data
Key Calculated Fields (logic examples):
New MRR
Total Revenue Change (%)
Cohort Analysis

![image](https://github.com/user-attachments/assets/623c26b9-3481-4a24-b178-24c858b7a429)
