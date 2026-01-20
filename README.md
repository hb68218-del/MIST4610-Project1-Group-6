# SEC Football Database Project

**MIST 4610 – Database Management & Analytics**  
**Project Group 6** — **Haeun Bae (Repository Owner & Group Lead)**, Dylan Ray (database support), Mattie Comte (project support)

---

## Project Objective

This project involved designing and analyzing a relational database to explore performance, operational, and behavioral trends within SEC college football. The goal was to move beyond raw game outcomes and demonstrate how structured data, advanced SQL analysis, and visualization can support informed decision making in a complex, real-world domain.

The project progressed from database schema design and data modeling to advanced analytical querying and dashboard development. Using SQL and Power BI, the analysis translated large, multi-dimensional datasets into actionable insights related to team performance, fan engagement, and external factors such as weather and officiating.

Overall, the project demonstrates the ability to scope an analytical problem, structure data for analysis, extract meaningful insights, and communicate results in a way that supports managerial and strategic decision making.

---

## Problem Overview

After completing database design and foundational SQL work in **Part 1**, Part 2 expands into **analytical storytelling**. Students investigate higher-level analytical questions, including:

- How weather conditions influence game outcomes  
- Whether referee strictness impacts scoring behavior  
- Attendance trends across teams and venues  
- How managers can interpret point differentials for strategic insights  

This phase connects database logic with data-driven decision making, emphasizing interpretation rather than raw query output.

---

## Tools and Technologies Used

- MySQL Workbench  
- Advanced SQL (complex joins, aggregations, analytical queries)  
- Power BI Desktop  
- PDF and document exports for formal submission  

---

## Data Used in Part 2

The dataset includes detailed SEC football information such as:

- Game outcomes and scoring margins  
- Weather conditions  
- Attendance figures  
- Referee data  
- Team and opponent attributes  

These data elements were queried, aggregated, and visualized to uncover meaningful performance and behavioral insights.

---

## Project Tasks Completed in Part 2

### Advanced SQL Querying

<img width="820" height="1002" alt="image" src="https://github.com/user-attachments/assets/0334c3bd-f01b-480f-b194-c92822cd7dcd" />
<img width="749" height="931" alt="image" src="https://github.com/user-attachments/assets/2e2b8fd7-b763-44c1-80bd-56bca616c796" />
<img width="750" height="823" alt="image" src="https://github.com/user-attachments/assets/b1bfe459-ccc7-407c-861b-be972816d8e9" />
<img width="746" height="1012" alt="image" src="https://github.com/user-attachments/assets/0059aa36-d671-4650-bd2c-3464ad00744e" />


Five complex SQL queries were created to analyze:

- Referee strictness  
- Weather impact on scoring and outcomes  
- Attendance patterns  
- Point differential behavior  
- Additional SEC analytics scenarios  

Each query was tested, documented, and exported with validated results.

---

### Data Visualization and Insights

<img width="977" height="1104" alt="image" src="https://github.com/user-attachments/assets/d6628838-008c-4d0a-8728-786c96eb8937" />

A Power BI dashboard was produced containing three primary visuals:

- Average Point Differential  
- Average Attendance by Home Team  
- Game Results by Weather  

Each visualization includes written managerial reasoning explaining how decision makers could interpret and act on the observed trends.

---

## Repository Contents

### `Final_Database.sql`
Complete SQL script including all tables, constraints, keys, and the finalized schema used for Part 2 analysis.

### `Final_EERDiagram_SQL.mwb`
MySQL Workbench model file containing the finalized EER diagram.

### `Final_EERDiagram_Png.png`
PNG export of the finalized EER diagram.

### `Dashboard.pbit`
Power BI dashboard file containing Part 2 visualizations.

### `3_Visualization_PDF.pdf`
PDF export of the three dashboard visuals:
- Average Point Differential  
- Average Attendance  
- Game Results by Weather  

### `3_Visualization_Managerial_Reasoning.docx`
Document explaining managerial insights derived from each dashboard visualization.

### `5_Complex_Query_and_Result_SC.docx`
Document containing all five SQL queries with screenshots of their outputs.

### `5_Complex_Queries/`
Folder containing individual SQL scripts for:
- Referee Strictness Query  
- Weather Impact Query  
- Attendance Query  
- Point Differential Query  
- Additional SEC Analytics Query  

Each script includes reasoning and expected analytical outcomes.
