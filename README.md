# Flight Price Analysis  

This repository contains a comprehensive data analysis of flight prices aimed at understanding the factors influencing airfare costs. Using Python's powerful data analysis and visualization libraries, the notebook explores various features of the dataset to derive meaningful insights.  

## Project Objectives  
The primary goals of this analysis are:  
- To identify key factors that influence flight prices.  
- To understand the impact of travel date, duration, and timing on airfare.  
- To explore trends across different airlines and routes.  
- To provide actionable insights for travelers and airline companies.  

## Dataset Description  
The analysis is conducted on a flight price dataset containing the following features:  
- **Date_of_Journey:** The date of travel.  
- **Duration:** Total journey time.  
- **Dep_Time and Arrival_Time:** Departure and arrival times.  
- **Airline:** The airline operating the flight.  
- **Source and Destination:** Departure and arrival cities.  
- **Price:** Ticket price.  

## Analysis Overview  
The notebook follows a structured approach:  

### 1. Data Loading and Inspection  
- Loading the dataset using `pandas`.  
- Initial inspection using `.head()`, `.info()`, and `.describe()` to understand data types, missing values, and statistical summaries.  

### 2. Data Cleaning and Preprocessing  
- Handling missing values to ensure data integrity.  
- Converting relevant columns to appropriate data types for analysis.  

### 3. Feature Engineering  
- **Date of Journey:** Extracting day, month, and year as separate features.  
- **Duration:** Breaking down journey duration into hours and minutes.  
- **Departure Time:** Extracting departure hour and minute for time-based analysis.  
- **Arrival Time:** Extracting arrival hour and minute to analyze travel patterns.  

### 4. Exploratory Data Analysis (EDA)  
- **Univariate Analysis:**  
  - Distribution of flight prices.  
  - Most frequent airlines and routes.  
  - Popular travel dates and times.  
- **Bivariate Analysis:**  
  - Relationship between price and duration.  
  - Impact of departure and arrival times on pricing.  
  - Price variations across airlines.  
- **Multivariate Analysis:**  
  - Combined effect of multiple factors on ticket pricing.  

### 5. Data Visualization  
Using `matplotlib` and `seaborn` for insightful visualizations, including:  
- Histograms and box plots to explore price distribution.  
- Line and bar charts for trend analysis.  
- Heatmaps to examine correlations between features.  

### 6. Key Insights and Findings  
- Analysis of price variations across different airlines.  
- Influence of journey duration and layovers on ticket pricing.  
- Seasonal trends impacting flight prices.  
- Optimal travel times for cost-effective bookings.  

## Requirements  
To run this notebook, the following dependencies are required:  
- Python 3.x  
- Jupyter Notebook  
- pandas  
- numpy  
- matplotlib  
- seaborn  

Install the necessary packages using:  
```bash
pip install pandas numpy matplotlib seaborn
