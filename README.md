# nhs-ae-performance-sql
SQL Analysis of NHS England A&amp;E performance data (2025-26), exploring breach rates, regional disparities and trust level performance across approximately 200 NHS organisations. Built in PostgreSQL using real open source NHS data.

# NHS A&E Performance Analysis, (SQL Project)

## Overview
An end to end SQL analysis of NHS England emergency care performance data (April 2025 — March 2026), examining  breach rates, regional disparities, and trust-level performance across England.

## Key Findings (thus far)
- NHS North West had the highest 4-hour breach rate at 42.6%
- Nationally only 60.6% of patients were seen within 4 hours, far below the 95% NHS target
more to be added as I progress on this project.

## Dataset
Source: NHS England , A&E Attendances and Emergency Admissions
Coverage: April 2025 to March 2026
Trusts: approximately 200 NHS organisations per month
(all datasets used are publicly available on the NHS website)

## Tools Used
- PostgreSQL (17.6)
- DBeaver

## SQL Concepts
- Table creation and bulk data loading (COPY)
- Aggregations (SUM, COUNT, ROUND)
- Filtering with WHERE and HAVING
- GROUP BY for regional and trust level breakdowns
- Window functions for rankings (to be completed)
- CTEs for readable complex queries (to be completed)
