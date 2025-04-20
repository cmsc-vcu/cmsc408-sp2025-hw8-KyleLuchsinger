# CMSC408-SP2025-HW8: World Bank Data Analysis

## Overview
This repository contains SQL queries for analyzing the World Bank Development Indicators dataset. The assignment focuses on developing SQL skills through progressive query complexity, from basic data exploration to advanced data transformation and analysis.

## Dataset
The dataset contains information about countries around the world, including:
- Country codes (2-alpha code, WB-2 code)
- Country names (short and long formats)
- Regional classifications
- Income group classifications

## Skills Demonstrated
This assignment demonstrates proficiency in the following SQL skills:
- Basic queries (SELECT, WHERE, ORDER BY)
- Data filtering and pattern matching
- Aggregation (COUNT, GROUP BY)
- Table creation and data manipulation (CREATE TABLE, UPDATE)
- Complex queries with subqueries and joins
- Pivot tables using CASE statements
- Cross joins for generating combinations
- Percentage calculations
- Common Table Expressions (CTEs)

## Repository Structure
- `helpers.py`: Contains utility functions for database connection and query execution
- `.env`: Configuration file for database credentials (not tracked in Git)

## Key Analyses
The queries in this project answer questions such as:
1. Distribution of countries across different regions
2. Income classification of countries by region
3. Identification of missing region-income group combinations
4. Percentage of countries in each income category
5. Statistical analysis of global wealth distribution

## Learning Takeaways
This project demonstrates how SQL can transform raw data into meaningful insights. Specifically:
- How to use SQL not just for data retrieval but for complex data analysis
- The power of CTEs for making complex queries more readable and maintainable
- Techniques for reshaping data using pivot tables
- Methods for calculating and visualizing percentage distributions

## Skills for Future Application
The SQL techniques learned in this assignment are applicable to:
- Business intelligence and data analysis
- Market research and trend identification
- Creating executive dashboards
- Comparative data analysis across multiple dimensions

## Technologies Used
- MySQL
- Python (for database connection and query execution)
- Quarto (for report generation)