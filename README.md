# Penalty Charge Notice Analysis in Nottingham

## Overview

This repository contains the analysis of Penalty Charge Notices (PCN) issued in Nottingham using Power BI. The analysis is based on a dataset spanning from the year 2015 to 2023. The findings are presented in a Power BI dashboard, and the insights drawn from the dataset are outlined below.

## Insights

### 1) Line Chart - Months(Issue Date) by Contravention
   - Observation: More penalties are noted during the winter or Christmas season.
   - Reasons:
     - Holiday Season: Increased activities, shopping, and travel.
     - Social Gatherings: Crowded areas with a lack of parking.
     - Weather conditions: Snow/ice leading to traffic-related penalties.

### 2) Pie Chart - Days(Issue Day) by Contravention
   - Observation: Fewer penalties on Sundays and Mondays across all years, but in 2022, Saturday, Sunday, and Monday have the least penalties.
   - Reasons:
     - Lower activity on Sundays.
     - Potential preference for public transport on Sundays and Mondays.

### 3) Tree Map - Penalties(Contravention Description) by Contravention Type
   - Observation: Most common penalty is for being in a bus lane, followed by parking violations.
   - Reasons:
     - Bus Lanes: Importance of keeping lanes clear for safety and smooth traffic.
     - Parking Issues: Suggests a need for better parking management.

### 4) Stacked Column Chart - Time(Issue Time) by Contravention
   - Observation: Peak hours for penalties issued from 9 am to 6 pm.
   - Reasons:
     - Peak business/operational hours with active use of parking areas.

### 5) Bar Chart - Street by Count of Penalty
   - Observation: Most common penalty is issued on Canal Street near Middle Hill (Westbound), followed by Canal Street near Albion Street (Eastbound) and Beck Street (Bus Gate).
   - Reasons:
     - High Traffic: Indicates a need for clear communication regarding parking.
     - Resource Allocation: Suggests the need for more resources in these busier areas.

## Data Processing

### Work Done on Data
   - Grouped the Contravention Description column to group distinct values for all datasets.
   - Used Power Query Editor to transform the Issue Time column to contain only time.
   - Formatted the Issue Date in the 2022 dataset using Data Analysis Expressions (DAX) expressions.

### Challenges
   - Data wasn’t grouped for the Contravention Description column initially.
   - Issue Time column contained both date and time.
   - Issue Date in the 2022 dataset was not in the proper hierarchy.

## Conclusion

The analysis provides valuable insights into the patterns of Penalty Charge Notices issued in Nottingham, highlighting specific trends during different months, days, times, and in various locations. These findings can inform decisions on resource allocation, communication strategies, and parking management in the city.
