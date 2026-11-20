# Deloitte Forensic Technology & Data Analytics

## Overview

This repository documents my completion of the **Deloitte Data Analytics Job Simulation** through **Forage**.

The simulation covered two areas: industrial machine telemetry analysis using Tableau, and a forensic technology task involving workplace gender pay equality data using Microsoft Excel. The forensic task focused on classifying equality scores to help identify potential pay disparities.

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

### 2. Forensic Technology — Workplace Pay Equality Analysis

Analyzed workplace equality scores across factory locations and job roles. This task was part of the simulation's Forensic Technology work, which examined potential gender-related pay disparities.

The classification formula uses `IFS` and `ABS` to classify the absolute equality score:
- **Fair:** absolute score is 10 or below
- **Unfair:** absolute score is above 10 and up to 20
- **Highly Discriminative:** absolute score is above 20

The extracted results are available in [Task 5 Equality Table.csv](./Task%205%20Equality%20Table.csv).

## Dashboard / Visual Preview

### Tableau Dashboard

![Deloitte Tableau Dashboard](deloitte-tableau-dashboard.svg)

The dashboard screenshot shows the two bar-chart views for unhealthy devices by factory and device type. The Tableau status bar shows 9 marks and a selected `SUM(Unhealthy)` value of 480.


## Data Files

- [Task 5 Equality Table.csv](./Task%205%20Equality%20Table.csv) — extracted equality-score records and classifications from the supplied Excel workbook.

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
- Applying forensic technology concepts to workplace pay-equality data.

## Note

This repository documents a learning experience completed through a job simulation. It is not a Deloitte production project or client engagement. The included screenshot and extracted data are supporting material for the simulation tasks.
