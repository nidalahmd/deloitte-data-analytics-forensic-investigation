# Deloitte Data Analytics Job Simulation

## Overview

This repository documents my completion of the **Deloitte Data Analytics Job Simulation** through **Forage**.

The simulation involved practical tasks in data analysis and forensic technology, using industrial telemetry data and employee equality-score data.

## Certificate

- **Program:** Deloitte Data Analytics Job Simulation
- **Provider:** Forage
- **Completion date:** August 23, 2026
- **Certificate period shown on certificate:** March 2026 – August 2026

## Tools Used

- Tableau
- Microsoft Excel
- Data analysis
- Data visualization
- Forensic technology

## Project Tasks

### 1. Telemetry Data Analysis using Tableau

Worked with Daikibo industrial telemetry data to explore device health and compare unhealthy device counts across factories and device types.

The dashboard contains:
- Unhealthy devices by factory
- Unhealthy devices by device type

### 2. Equality Score Classification using Microsoft Excel

Analyzed equality scores across factory job roles using the supplied Excel workbook.

The workbook contains:
- Factory
- Job Role
- Equality Score
- Equality class

The classification formula uses `IFS` and `ABS` to classify the absolute equality score:
- **Fair:** absolute score is 10 or below
- **Unfair:** absolute score is above 10 and up to 20
- **Highly Discriminative:** absolute score is above 20

## Dashboard / Visual Preview

### Tableau Dashboard

![Deloitte Tableau Dashboard](deloitte-tableau-dashboard.jpg)

The dashboard screenshot shows the two bar-chart views for unhealthy devices by factory and device type. The Tableau status bar shows 9 marks and a selected `SUM(Unhealthy)` value of 480.

> This is a screenshot preview. The editable Tableau workbook (`.twb` or `.twbx`) was not included in the supplied files.

## Dataset and Supporting Files

- `daikibo-telemetry-data.zip` — compressed Daikibo industrial telemetry JSON dataset (160,704 records). Extract the ZIP to access the JSON file.
- `Task 5 Equality Table.xlsx` — equality-score classification workbook.
- `Deloitte-Data-Analytics-Job-Simulation-Certificate.pdf` — certificate of completion.
- `deloitte-tableau-dashboard.jpg` — Tableau dashboard screenshot displayed above.

## Skills Demonstrated

- Data analysis
- Data visualization
- Tableau dashboard creation
- Microsoft Excel
- Data classification
- Interpreting operational telemetry
- Forensic technology

## What I Learned

- Exploring industrial telemetry data to understand equipment health.
- Comparing unhealthy device counts across factories and device types.
- Using Tableau to communicate data through visualizations.
- Applying Excel logic to classify equality scores.
- Interpreting data in the context of forensic analysis.

## Note

This repository documents a learning experience completed through a job simulation. It is not a Deloitte production project or client engagement. The files are included as supporting material for the simulation tasks.
