# ✈️ Flight Delay Pattern Analyzer --- Final Report

## 1. Introduction

This report summarizes analysis of U.S. flight delay patterns across
airports, airlines, seasons, and times of day.

## 2. Dataset Overview

Includes fields such as: - FL_DATE - ORIGIN, DEST - MKT_UNIQUE_CARRIER -
CRS_DEP_TIME - DEP_DELAY, ARR_DELAY - Cancellation details

### Cleaning Steps

-   Removed canceled flights\
-   Dropped irrelevant fields\
-   Extracted departure hour\
-   Added shift label\
-   Removed missing delays

## 3. Visualizations & Analysis

### 3.1 Most Delayed Airports

Shows which airports experience highest departure delays.

### 3.2 Monthly Delay Trends

Seasonal peaks:\
- Summer thunderstorms\
- Winter snow/fog

### 3.3 Morning vs Evening Delay Comparison

Evening flights are delayed by \~4 minutes more than morning flights.

### 3.4 Airport vs Airline Heatmap

Reveals bottlenecks at airport--airline combinations.

## 4. Key Insights

-   Evening delays accumulate over the day\
-   Seasonal patterns strongly affect delays\
-   Some airports consistently perform poorly\
-   Airline delays vary by airport

## 5. Conclusion

The project provides meaningful insights into delay behavior across the
U.S. flight network.

## 6. Future Work

-   Include weather data\
-   Predictive modeling\
-   Dashboard development

## 7. Author

Rahul
