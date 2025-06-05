# Hospital Wait Time Reduction Analysis

## Project Overview

This Excel project looks at patient wait times in a hospital to find patterns and give suggestions to reduce waiting. The data was cleaned and organized, and then Pivot Tables and Pivot Charts were used to find useful insights about wait times based on patient type, weekdays, and hours of the day.

## Problem Statement

Hospitals often face long patient wait times, which can lead to unhappy patients and slower service. This project helps identify when and why wait times are high so that hospital staff can make better decisions and improve service.

## Methodology

### Data Cleaning

- Fixed all date formats to be the same.
- Created a **Wait Time** column by subtracting entry time from completion time.
- Added a **Weekday** column from the Date to see patterns across days.
- Created an **Entry Hour** column from the Entry Time to study time-based trends.

### Data Analysis Using Pivot Tables & Charts

- Made pivot charts to compare average wait times by financial class.
- Compared wait times and number of patients on different days of the week.
- Analyzed wait times and patient volume by hour of the day using combo charts.

## Key Insights

### By Financial Class

- **Medicare** patients waited the longest (**58 mins**), while **Private** patients had the shortest wait (**40 mins**).
- Patients with **Corporate, HMO, and Insurance** classes had similar wait times (**44–46 mins**).

### By Weekday

- **Monday** had the highest number of patients and longest wait time.
- Mid-week days like **Wednesday and Thursday** also had high wait times even with fewer patients.
- **Saturday** had lower patient numbers but wait times didn’t improve much.

### By Hour of the Day

- **Morning hours** was the busiest time with high wait times.

## Suggestions to Reduce Wait Times

1. **Spread out Monday appointments** – Encourage patients to book on less busy days.
2. **Improve Medicare processing** – Since Medicare patients wait the longest, their process can be made faster.
3. **Add more staff during morning hours** – This will help handle the rush better.
4. **Track this data monthly** – Keep checking which days and hours have the most delays to adjust staff or scheduling.
