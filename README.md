# Agent Transport Payout Analysis

## Project Overview
This project focuses on cleaning, processing, and analysing agent attendance and login records to determine transport payout eligibility.

Using Python and Pandas, the raw agent transport data is transformed into a structured dataset, with payout calculations based on attendance status, assigned shift, and actual login time.

## Objectives
- Clean and organise raw agent transport records.
- Review agent attendance and login information.
- Apply shift-based login time conditions.
- Determine eligible agents for transport payments.
- Automate payout calculations using Python.

## Tools and Technologies
- **Python** – Data processing and automation.
- **Pandas** – Data cleaning, manipulation, and analysis.
- **Jupyter Notebook** – Development and execution environment.

## Payout Calculation
The project applies the following conditions:

**Attendance requirement:** Only agents with a Present (`P`) attendance status qualify for payout consideration. Agents who do not meet the specified conditions receive zero payout.

## Data Processing
The analysis involves:
1. Importing the raw Excel dataset into Pandas.
2. Removing unnecessary columns.
3. Handling different data formats in the login time column.
4. Preparing date and time fields for analysis.
5. Creating a payout column.
6. Applying a custom Python function to calculate each agent's payout.

## Final Output
The processed dataset contains agent information, attendance status, shift details, actual login time, and the calculated transport payout.

## Project Purpose
This project demonstrates the application of Python in automating operational reporting and payment-related calculations, reducing manual effort and improving consistency in data processing.

---
**Author:** Olorunshola Moses  
**Skills Demonstrated:** Python | Pandas | Data Cleaning | Data Transformation | Business Logic Automation
