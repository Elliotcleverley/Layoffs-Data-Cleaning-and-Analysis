Project Overview

This project involves data cleaning and exploratory analysis of a global layoffs dataset using MySQL. The objective was to transform raw, unformatted data into a structured format suitable for economic analysis.

Technical Workflow

Data Staging
Created staging tables to ensure raw data preservation throughout the transformation process

duplicate rows
Implemented ROW_NUMBER() and CTE logic to identify and isolate duplicate observations across multiple dimensions

Standardisation
Utilised TRIM and TRAILING functions for string manipulation and converted text-based dates into DATE objects for time-series analysis

Handling Missing Data
Executed self-joins to backfill missing industry values based on company-level observations and filtered out entries lacking critical layoff magnitude data

Quality Assurance
Developed validation queries using CASE statements to calculate missing value percentages and ensure data consistency

Exploratory Data Analysis 

Calculated total layoffs by year and month 

Aggregated layoffs by country and industry to assess sector-specific volatility

Utilised LIMIT and GROUP BY functions to identify high-impact company outliers and regional concentrations
