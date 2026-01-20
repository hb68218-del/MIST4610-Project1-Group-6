---
title: "College Football SQL Analytics Project"
author: "Sally Bae" and 
output:
  html_document:
    toc: true
    toc_depth: 2
    theme: flatly
---

## Project Overview

This project explores NCAA college football performance and fan engagement through a relational SQL database. The goal was to transform raw sports data into structured insights that support data driven decision making for athletic departments, analysts, and leadership.

Using SQL and Power BI, the project analyzes team performance, attendance trends, and external game factors such as weather and officiating to understand what drives outcomes on and off the field.

## Objectives

- Design and implement a normalized relational database for college football analytics  
- Analyze team and game level performance using complex SQL queries  
- Identify trends in attendance and fan engagement  
- Translate technical SQL outputs into clear business insights through dashboards  

## Dataset Scope

The database integrates multiple data dimensions including:

- Teams and conferences  
- Games and schedules  
- Scores and outcomes  
- Attendance figures  
- Weather conditions  
- Officiating assignments  

The schema was designed to support scalable analysis across seasons, teams, and venues.

## Database Design

- Built a relational schema with primary and foreign keys to enforce data integrity  
- Applied normalization principles to reduce redundancy  
- Modeled one to many and many to many relationships where appropriate  
- Optimized tables for analytical querying and joins  

## SQL Analysis

Key analyses include:

- Team performance comparisons across seasons and conferences  
- Home vs away performance trends  
- Attendance patterns by team, location, and game conditions  
- Impact of weather and officiating on game outcomes  
- Aggregate and window functions for trend analysis  

### Advanced SQL Techniques Used

- Multi table joins  
- Subqueries and common table expressions  
- Aggregations and grouping  
- Conditional logic and filtering  

## Visualization and Insights

SQL query outputs were connected to Power BI to create interactive dashboards that:

- Highlight performance trends and anomalies  
- Compare teams and conferences visually  
- Present attendance drivers in an executive friendly format  
- Support managerial level decision making  

## Tools and Technologies

- SQL (MySQL or PostgreSQL)  
- Power BI  
- GitHub  
- Relational database design principles  

## Repository Structure

```text
College-football-analytics-SQL/
│
├── data/
│   ├── raw_data
│   └── cleaned_data
│
├── sql/
│   ├── table_creation.sql
│   ├── data_inserts.sql
│   └── analysis_queries.sql
│
├── dashboards/
│   └── powerbi_dashboard.pbix
│
├── documentation/
│   ├── data_dictionary
│   └── schema_diagram
│
└── README.md
