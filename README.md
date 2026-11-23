# Motor-Insurance-Operations-Analytics
Motor insurance operations analytics project using SQL and Power BI to analyze request volumes, processing performance, SLA breaches, policy issuance, inspections, and endorsements.
Motor Insurance Operations Analytics

Project Overview

<img width="1327" height="811" alt="image" src="https://github.com/user-attachments/assets/ce65b475-9673-4f03-ab1e-b080d4afbc4f" />


This project analyzes motor insurance operations to evaluate operational performance, request completion, turnaround time (TAT), SLA compliance, process distribution, and premium performance.

The objective is to transform operational data into meaningful business insights using SQL and Power BI, helping identify process bottlenecks, improve efficiency, and support data-driven decision-making.

Business Problem

Motor insurance operations involve multiple processes, including policy issuance, inspections, and endorsements. Monitoring request volumes, processing turnaround time, SLA breaches, and completion rates is essential for maintaining operational efficiency and customer satisfaction.

This project focuses on answering key business questions:

What is the overall request volume?

What is the request completion rate?

Which processes experience the highest SLA breach rates?

What is the average processing turnaround time?

How does request volume vary over time?

Which operational areas require improvement?

How does operational performance vary across customer cities?

Project Objectives

Analyze motor insurance operational data using SQL.

Monitor key operational performance indicators.

Identify SLA breaches and processing delays.

Analyze request distribution across operational processes.

Evaluate request status and completion performance.

Build an interactive Power BI dashboard.

Generate actionable business insights and recommendations.

Tools & Technologies

Tool

Purpose

SQL

Data analysis, querying, KPI calculations, and business insights

Power BI

Interactive dashboard development and data visualization

Excel

Dataset exploration and data preparation

GitHub

Project documentation and version control

Dataset Description

The project uses a synthetic motor insurance operations dataset containing 1,200 operational records.

The dataset includes information related to:

Request ID

Policy ID

Request date and month

Request type

Business type

Sales channel

Vehicle type

Vehicle age

Customer city

Priority

Assigned team

Processed by

Document status

Payment status

Premium amount

SLA hours

Processing TAT

Request status

SLA breach indicator

Pending/rejection reason

Inspection details

Endorsement details

Disclaimer: The dataset used in this project is synthetic and created for analytical and demonstration purposes. It does not contain actual customer or company data.

SQL Analysis

SQL was used to perform operational analysis and answer business questions.

Key Areas of Analysis

Total request volume

Unique policy count

Request status distribution

Completion rate

Pending and rejected requests

SLA breach analysis

SLA breach rate by process

Average processing TAT

Processing performance by team

Processing performance by employee

Policy issuance analysis

Inspection analysis

Endorsement analysis

Sales channel performance

Monthly request trends

Premium analysis

Power BI Dashboard

Overview Dashboard

The dashboard provides a consolidated view of motor insurance operations.

Key Performance Indicators

KPI

Value

Total Requests

1,200

Completed Requests

940

Completion Rate

78.33%

SLA Breach Rate

26.83%

Average Processing TAT

22.91 Hours

Total Premium

32.58M

Dashboard Visualizations

Monthly Request Volume Trend

Request Distribution by Process

SLA Breach Rate by Process

Request Status Distribution

Customer City Slicer

KPI Cards

Key Business Insights

1. Overall Operational Performance

The dataset contains 1,200 requests, of which 940 have been completed, resulting in a completion rate of 78.33%.

This indicates that a portion of requests remain pending or in other non-completed statuses and may require further operational monitoring.

2. SLA Performance

The overall SLA breach rate is 26.83%.

This highlights an opportunity to improve operational efficiency, identify processing bottlenecks, and strengthen SLA monitoring.

3. Process Distribution

Policy Issuance represents the largest share of operational volume, with 677 requests.

This indicates that policy issuance is the primary process contributing to overall operational workload.

4. Endorsement Performance

Endorsement has the highest SLA breach rate among the analyzed processes.

Further investigation into workload distribution, documentation dependencies, process complexity, and turnaround time may help identify the root causes of delays.

5. Monthly Request Trends

Request volumes vary across months, allowing operational teams to monitor workload fluctuations and identify periods of higher demand.

Business Recommendations

Based on the dashboard analysis:

Investigate the root causes of SLA breaches in endorsement operations.

Monitor pending requests and prioritize aging cases.

Improve workload distribution across operational teams.

Track processing TAT by request type and sales channel.

Monitor monthly request volumes to support resource planning.

Introduce regular SLA performance reviews.

Develop employee-level performance monitoring.

Use city-level analysis to identify regional operational variations.

Project Structure

Motor-Insurance-Operations-Analytics/
│
├── README.md
│
├── Dataset/
│   ├── insurance_operations.csv
│   └── Data_Dictionary.xlsx
│
├── SQL/
│   └── Motor_Insurance_Analysis.sql
│
├── PowerBI/
│   └── Motor_Insurance_Dashboard.pbix
│
├── Dashboard_Screenshots/
│   └── Overview.png
│
└── Project_Documentation/
    └── Business_Insights.pdf

Skills Demonstrated

SQL Querying

Data Analysis

KPI Development

Operational Performance Analysis

SLA Monitoring

Turnaround Time Analysis

Power BI Dashboard Development

Data Visualization

Business Insight Generation

Analytical Problem Solving

Conclusion

This project demonstrates how operational data can be transformed into actionable insights using SQL and Power BI.

By analyzing request volumes, completion rates, processing turnaround time, and SLA breaches, the dashboard helps identify areas requiring operational attention and supports better decision-making.

The project combines technical analytical skills with business understanding of motor insurance operations.

Author: Anurag Kumar
Domain: Motor Insurance Operations & Analytics
Tools: SQL | Power BI | Excel
