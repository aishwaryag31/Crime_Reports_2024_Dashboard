# Crime_Reports_2024_Dashboard

## Project Overview

This repository contains the **Crime Report 2024 Dashboard**, an interactive Power BI tool designed to explore various aspects of crime data from 2024. It provides insights into time-based crime patterns, geographic hotspots, severity analysis, and offense trends, enabling users to understand and address crime-related issues effectively.

## Key Features

### Crime Clock: Patterns by Time & Day

The **Crime Clock** section provides a comprehensive overview of crime patterns based on time and day. It displays the total number of crimes recorded in 2024, highlights the hour of the day with the highest crime rate, and identifies the day of the week with the most crimes. The shift analysis indicates whether crimes occur most frequently during the day, evening, or midnight shifts. Visualizations include a line chart for hourly crime patterns, a bar chart for weekly crime trends, and a heatmap for hourly crime intensity by day of the week. This section reveals key insights, such as crimes peaking during the evening on Fridays and the busiest hour being 12 PM.

### Crime Map: Geographic Hotspots

The **Crime Map** section focuses on the spatial distribution of crimes. Key features include neighborhoods with the most and least crimes, highlighting high- and low-crime areas. It uses a Crime Hotspot Map to visually represent crime density across neighborhoods and provides ward-wise severity analysis using bar charts to display crime severity levels (low, medium, high). A treemap for police service area crime distribution offers a detailed look at where crimes are concentrated. This section pinpoints high-risk areas like Cluster 2, which recorded the most crimes, and provides an understanding of theft-related crimes dominating specific regions.

### Crime Severity and Offense Analysis

The **Crime Severity and Offense Analysis** section dives into the severity and types of crimes committed. It provides the total count of high-severity incidents and identifies the shift with the most high-severity crimes. The average crime duration is also displayed, offering insights into the time spent on criminal activities. Visualizations include a pie chart for crime severity levels, a bar chart for crime behavior during shifts, a line chart for trends in specific crime categories, and a bar chart for weapon usage patterns. This section shows that guns are the most commonly used weapons in crimes, with high-severity crimes frequently occurring during the midnight shift.

## Dataset Details

The dataset used for the **Crime Report 2024 Dashboard** includes detailed information about crimes reported in 2024. Below is an overview of the fields and a note on additional calculated columns used for analysis:

### Fields

- **Crime ID**: Unique identifier for each crime.
- **Type of Crime**: Classification of crime (e.g., robbery, theft, homicide, etc.).
- **Shift**: Time of crime (day, evening, or midnight).
- **Day of the Week**: Day when the crime occurred.
- **Offense Method**: Weapon or method used in the crime (e.g., gun, knife, others).
- **Location**: Block address of the crime.
- **Ward**: City ward where the crime occurred.
- **District**: Jurisdictional district responsible for the area.
- **PSA (Police Service Area)**: Police zone where the crime occurred.
- **Latitude/Longitude**: Geographical coordinates of the crime scene.
- **Neighborhood Cluster**: Identifies high-level geographic clusters for analysis.
- **Voting Precinct**: Electoral precinct in which the crime took place.
- **Report Date**: The date and time the crime was reported.
- **Start/End Date**: Timeframe when the crime occurred.

Additionally, several calculated columns, such as crime duration and severity indices, were created to support deeper analysis and visualizations.

## Tools and Technologies

- **Power BI**: Dashboard creation and data visualization.
- **Python**: Data cleaning and preprocessing (Pandas, NumPy).
- **Data Source**: Compiled crime dataset for 2024.

## Future Enhancements

- **Real-Time Data Updates**: Incorporate API integration for live crime data updates.
- **Predictive Analytics**: Use machine learning to predict crime trends and high-risk zones.
- **Community Feedback Integration**: Add features to gather feedback from the public on safety concerns.
- **Resource Allocation Recommendations**: Provide insights for optimizing police patrols and resource distribution.

