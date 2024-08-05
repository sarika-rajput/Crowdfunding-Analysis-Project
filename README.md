# Crowdfunding Analysis Project

## Table Of Contents

- [Project Overview](#project-overview)
- [Dataset Details](#dataset-details)
- [Tools Used](#tools-used)
- [Data Cleaning And Preperation](#data-cleaning-and-preperation)
- [Power BI Dashboard](#power-bi-dashboard)
- [Insights](#insights)
- [Conclusion](#conclusion)

## Project Overview

Crowdfunding is the practice of funding a project or venture by raising small amounts of money from a large number of people, typically via the Internet. Kickstarter is one of the most famous crowdfunding websites. Thousands of creative projects are funded on Kickstarter at any given moment, each independently created and crafted by its originator. This project uses tools like Excel, SQL, Power BI, and Tableau to analyze Kickstarter data, providing valuable insights into trends, success rates, and factors influencing project outcomes. Kickstarter hosts over 300k meticulously curated projects on its platform. This dashboard offers a comprehensive analysis of Kickstarter's vast repository of creative ventures, helping users understand the dynamics of crowdfunding and make data-driven decisions.

## Dataset Details

- **Domain**: Finance - Crowdfunding Analytics
- **Project Name**: Crowdfunding Analysis
- **Source**: Kickstarter
- **Type**: Excel Data
- **Size**: 300,000+ records

## Tools Used

- **Excel**: Data Cleaning
- **Power BI**: Dashboard Creation
- **Tableau**: Dashboard Creation
- **SQL**: Data Analysis


## Data Cleaning And Preperation

   - Converted date fields from Epoch time to natural time format. For reference on Epoch time conversion, see [Epoch Time Converter](https://www.epochconverter.com/).

   - Created a Calendar Table using the `Created Date` column.
   - Added the following columns to the Calendar Table using formulas:
     - **Year**
     - **Month No** (`Monthno`)
     - **Month Full Name** (`Monthfullname`)
     - **Quarter** (`Quarter` with values Q1, Q2, Q3, Q4)
     - **Year-Month** (`YearMonth` in YYYY-MMM format)
     - **Weekday No** (`Weekdayno`)
     - **Weekday Name** (`Weekdayname`)
     - **Financial Month** (`FinancialMonth` with April = FM1, May = FM2, ..., March = FM12)
     - **Financial Quarter** (`FinancialQuarter` based on Financial Month, with values FQ-1, FQ-2, ...)

   - Constructed the data model using the attached Excel files.

   - Converted the goal amount into USD using a static USD exchange rate.
     
## Power BI Dashboard
## Page .1

![Dashboard 1](https://github.com/user-attachments/assets/10c702f6-1b20-4af5-83c5-8add3ea70c4a)
## Page .2

![Dashboard 2](https://github.com/user-attachments/assets/3dff07e2-f873-465f-ac8a-a074002bd238)
## Page .3

![Dashboard 3](https://github.com/user-attachments/assets/8faa7ed6-4173-4192-8c87-beb6c389a915)

## Insights

1. **Projects Overview KPI**:
   - **Total Number of Projects Based on Outcome**: Counts all projects categorized by their final outcome (e.g., successful, failed).
   - **Total Number of Projects Based on Locations**: Shows the count of projects segmented by their geographical locations.
   - **Total Number of Projects Based on Category**: Displays the number of projects within each specified category.
   - **Total Number of Projects Created by Year, Quarter, Month**: Tracks the number of projects initiated over different time periods (yearly, quarterly, monthly).

2. **Successful Projects**:
   - **Amount Raised**: Total funds accumulated from successful projects.
   - **Number of Backers**: Total count of supporters who funded successful projects.
   - **Average Number of Days for Successful Projects**: Average duration from project launch to successful funding.

3. **Top Successful Projects**:
   - **Based on Number of Backers**: Lists the top successful projects by the number of backers.
   - **Based on Amount Raised**: Lists the top successful projects by the total amount of funds raised.

4. **Percentage of Successful Projects**:
   - **Overall**: Proportion of successful projects relative to all projects.
   - **By Category**: Success rate of projects within each category.
   - **By Year, Month, etc.**: Success rate of projects over different time periods.
   - **By Goal Range**: Success rate of projects categorized by predefined funding goal ranges.

## Conclusion 

The "Kickstarter Crowdfunding Analysis Dashboard" offers actionable, data-driven insights designed to enhance the success of your crowdfunding projects. This dashboard allows users to identify top-performing project categories and goal ranges, facilitating more effective audience targeting. It also reveals historical trends in successful projects across different time periods—yearly, monthly, and quarterly—enabling optimization of project timing. Additionally, it uncovers funding trends within various project categories, helping to set realistic funding goals. By leveraging these insights, users can make informed decisions, gain a competitive advantage, and stay ahead of emerging crowdfunding trends, ultimately increasing the likelihood of successful projects. 







