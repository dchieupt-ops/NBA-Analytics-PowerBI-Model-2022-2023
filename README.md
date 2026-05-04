# 🏀 NBA Analytics PowerBI Model (2022-2023)

## 📌 Project Overview
This project analyzes the correlation between NBA player performance and their salaries for the 2022-2023 season. Using Power BI and SQL, we identify the most efficient players and team payroll structures.
- **Course:** BTMA 331 Final Project (Group 14)
- **Team Members:** Hieu Dinh, Darren Keilty, Eddie Li

## 📽 Video Presentation & Demo
Watch our full project walkthrough and Power BI dashboard demonstration:(https://youtu.be/em3CBjauJOs?si=WjOowd9WblS3g_Yk)

## 🏗 Data Architecture & SQL Integration
A key strength of this project is the professional data handling process. We utilized a **SQL Server** hosted by the university to manage and transform raw data before visualization.

### Data Modeling (Star Schema)
We designed a robust **Star Schema** to optimize performance and query efficiency. The model consists of Fact and Dimension tables as shown below
**Technical Workflow:**
1. **ETL Process:** Extracted raw NBA boxscores and salary data from Kaggle.
2. **SQL Transformation:** Used SQL for data cleaning, handling missing values, and joining relational tables (Players, Teams, Salaries) on the server.
3. **Power BI Connection:** Connected Power BI to the SQL database to build the analytical model.

## 📊 Key Insights from Dashboard
Based on our Power BI model:
- **Positional Salary:** Point Guards (PG) account for the highest portion of annual salaries at **22.68%**.
- **Team Payroll:** **LA Clippers (LAC)** ranked #1 in total team salary for the season.
- **Efficiency:** We analyzed players based on Points, Assists, Rebounds, and Defensive stats (Steals/Blocks).

## 📂 Data Sources
Data was sourced from Kaggle: [NBA 2022-2023 Advanced Boxscores](https://www.kaggle.com/datasets/szymonjwiak/nba-2022-2023-advanced-boxscores?select=games.csv)

## 🛠 Tech Stack
- **SQL (Server-side):** Data cleaning, ETL, and relational management.
- **Power BI:** Data Modeling (DAX), Relationship management, and Visualization.
- **Python (Optional):** Used for advanced statistical efficiency analysis.
- **Excel/CSV:** For static data validation and local storage.
