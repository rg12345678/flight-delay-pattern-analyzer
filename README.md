<<<<<<< HEAD
# ✈️ Flight Delay Pattern Analyzer

A complete data analysis project exploring U.S. flight delays across
airports, airlines, seasons, and times of day using Python, Pandas,
Matplotlib, and Seaborn.

## 📌 Project Overview

Flight delays are a major inconvenience for passengers and a challenge
for airline operations.\
This project analyzes real-world U.S. flight data to uncover patterns
and insights such as:

-   Which airports experience the most delays\
-   Seasonal delay trends (month-wise)\
-   Whether evening flights are more delayed than morning flights\
-   Which airlines perform better or worse at specific airports

The project includes data cleaning, feature engineering, multiple
visualizations, and a final insights report.

## 🧰 Tech Stack

-   **Python 3**
-   **Pandas**
-   **NumPy**
-   **Matplotlib**
-   **Seaborn**
-   **Jupyter Notebook** 

## 📂 Project Structure

    Flight_Delay_Analyzer/
    │
    ├── data/
    │     └── flights.csv
    ├── notebooks/
    │     └── analysis.ipynb
    ├── reports/
    │     └── Flight_Delay_Report.md
    └── README.md

## 🔧 Data Preparation & Cleaning

Key preprocessing steps:

-   Removed canceled flights (`CANCELLED = 0`)
-   Dropped irrelevant or mostly empty columns (`TAIL_NUM`,
    `CANCELLATION_CODE`)
-   Extracted departure hour from scheduled time
-   Added `Shift` label (Morning vs Afternoon/Evening)
-   Removed rows with missing arrival delays
-   Created a clean dataset ready for visualizations

## 📊 Visualizations Included

This project includes several clear and informative plots:

### 1. Most Delayed Airports (Bar Chart)

### 2. Monthly Delay Trends (Time Series)

### 3. Morning vs Evening Delays (Boxplot)

### 4. Airport vs Airline Delay Heatmap

## 🔍 Key Insights

-   Evening flights have \~4 minutes more delay on average\
-   Seasonal delay spikes (summer storms, winter snow)\
-   Certain airports consistently show higher delays\
-   Airline performance varies across airports

## 🚀 How to Run This Project

### Clone the repository

``` bash
git clone https://github.com/your-username/flight-delay-pattern-analyzer.git
cd flight-delay-pattern-analyzer
```

### Install dependencies

``` bash
pip install -r requirements.txt
```

### Run the analysis

``` bash
python src/analysis.py
```

## 📈 Future Enhancements

-   Add weather data\
-   Build delay prediction models\
-   Create dashboard with Streamlit/Plotly\
-   Generate airline-specific reports

## 🧑‍💻 Author

Rahul

## ⭐ Support

Give this repo a ⭐ on GitHub!
=======
# flight-delay-pattern-analyzer
A data analysis project exploring airport, airline, and seasonal flight delay patterns.
>>>>>>> 8f243a30a7ab7a35465318b7624e567ab24ae159
