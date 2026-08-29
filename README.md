# Formula Bharat Performance Dashboard

## About the Project

This project is an interactive Power BI dashboard developed to analyze Formula Bharat racing performance data.

The dashboard provides insights into driver performance, racing sessions, speed, lap times, battery usage, and vehicle temperature parameters.

The project contains three main dashboard pages:

- Executive Summary
- Driver Performance Analysis
- Vehicle Health & Temperature Analysis

## Dataset

The raw dataset contains Formula Bharat racing performance information.

The main dataset contains 2,700 records and includes information such as:

- Session ID
- Session Date
- Driver Name
- Team
- Track
- Lap Number
- Lap Time
- Average Speed
- Top Speed
- Battery Usage
- Tire Temperature
- Brake Temperature
- Motor Temperature
- Track Temperature
- Weather
- Position
- DNF
- Comments

## Dashboard Pages

### 1. Executive Summary

The Executive Summary provides an overview of the overall racing performance.

Key metrics include:

- Number of Drivers
- Peak Speed Recorded
- Average Lap Time
- Average Battery Usage
- Number of Sessions
- Average Speed

The page also includes:

- Lap time trend over sessions
- Total laps completed by driver
- Driver filter
- Session date filter
- Weather filter

This page is designed to provide a quick overview of the overall performance.

### 2. Driver Performance Analysis

This page focuses on comparing individual driver performance.

The dashboard includes:

- Average Lap Time by Driver
- Average Speed by Driver
- Peak Speed by Driver
- Driver Performance Matrix
- Fastest Driver
- Peak Speed
- Best Lap Time
- Low Battery Usage

Users can filter the analysis using:

- Session Date
- Driver Name
- Weather

This page helps identify differences in driver speed, consistency and lap performance.

### 3. Vehicle Health & Temperature Analysis

This page focuses on vehicle operating conditions and temperature-related performance.

Key metrics include:

- Average Tire Temperature
- Maximum Tire Temperature
- Average Brake Temperature
- Average Motor Temperature
- Average Track Temperature

The dashboard also contains:

- Battery Usage by Driver
- Motor Temperature vs Average Speed
- Tire Temperature vs Brake Temperature by Driver

Filters are available for:

- Weather
- Session Date
- Driver Name

This page can be used to identify relationships between vehicle temperature, battery usage and racing performance.

## Key Analysis

The dashboard allows users to analyze:

- Driver performance
- Lap time consistency
- Average and peak speed
- Battery usage
- Tire temperature
- Brake temperature
- Motor temperature
- Track temperature
- Weather conditions
- Racing sessions

The interactive filters allow the analysis to be narrowed down by driver, date and weather.

## Tools Used

- Power BI
- Power Query
- DAX
- Microsoft Excel

## Dashboard Features

- Interactive KPI cards
- Slicers
- Driver-level analysis
- Performance comparison
- Temperature analysis
- Speed analysis
- Lap time analysis
- Interactive navigation between dashboard pages

## Project Structure

```text
Formula-Bharat-Performance-Dashboard/
│
├── Formula_Bharat_Performance_Dashboard.pbix
├── Formula_Bharat_Raw_Dataset.xlsx
└── README.md
