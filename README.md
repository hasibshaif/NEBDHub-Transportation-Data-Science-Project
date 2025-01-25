# NYC Traffic Crash Data Analysis

## Project Overview

This project analyzes New York City's traffic crash data to identify patterns, trends, and insights that can inform safety improvements. The analysis is structured into six milestones, each focusing on a specific aspect of data analysis, culminating in actionable recommendations for stakeholders such as the Department of Transportation and the Federal Highway Authority.

## Milestones

### 1. Data Preparation

- **Objective**: Set up the analytical environment, install necessary packages, access the NYC traffic crash dataset, and perform initial exploratory data analysis (EDA).
- **Actions**:
  - Configured the environment in Google Colab.
  - Installed Python libraries including pandas, numpy, and matplotlib.
  - Loaded the NYC traffic crash dataset.
  - Conducted basic EDA to understand data structure and key statistics.

### 2. Data Ethics, Pre-processing, and Exploration

- **Objective**: Assess the dataset for missing values and inconsistencies, and decide on appropriate handling methods to ensure ethical and accurate analysis.
- **Actions**:
  - Identified missing and anomalous data points.
  - Implemented strategies such as imputation and removal for handling missing data.
  - Ensured data processing adhered to ethical standards, maintaining data integrity and privacy.

### 3. Time Series Analysis

- **Objective**: Analyze temporal trends in traffic crashes to identify patterns over time.
- **Actions**:
  - Converted date and time columns into datetime objects.
  - Resampled data to examine trends on daily, monthly, and yearly bases.
  - Visualized crash frequencies over time to identify peaks, trends, and anomalies.

### 4. Geospatial Analysis

- **Objective**: Explore the geographical distribution of traffic crashes across NYC.
- **Actions**:
  - Utilized latitude and longitude data to map crash locations.
  - Created heatmaps to identify high-density crash areas.
  - Analyzed crash distributions across different boroughs and neighborhoods.

### 5. Self-Guided Research Question

- **Objective**: Investigate the impact of weather conditions, particularly precipitation, on the frequency and severity of traffic crashes.
- **Actions**:
  - Integrated external weather data corresponding to crash dates and locations.
  - Analyzed correlations between weather variables (e.g., precipitation levels) and crash metrics.
  - Visualized findings to assess the influence of weather on crash occurrences.

### 6. Virtual Poster Board Creation: Data Storytelling

- **Objective**: Synthesize research findings into a concise, visual format to effectively communicate insights and recommendations.
- **Actions**:
  - Developed a one-page virtual poster summarizing the research question, methodology, key findings, and recommendations.
  - Emphasized actionable insights for stakeholders to enhance road safety.
  - Included visualizations and narratives to support data-driven conclusions.

## Key Findings

- **Temporal Trends**: Identified specific time periods with higher crash frequencies, suggesting targeted times for interventions.
- **Geospatial Patterns**: Recognized high-risk areas within NYC, indicating where infrastructure improvements could be prioritized.
- **Weather Impact**: Found that precipitation levels did not have a significant correlation with crash frequency or severity, suggesting other factors play a more critical role.

## Recommendations

- **Targeted Enforcement**: Increase traffic law enforcement during identified high-risk time periods.
- **Infrastructure Enhancements**: Focus on improving road safety features in high-density crash areas.
- **Further Research**: Investigate other potential factors influencing crash occurrences, such as driver behavior or traffic volume.

## How to Use This Repository

1. **Google Colab Notebook**: Access the `NYC_Traffic_Crash_Analysis.ipynb` notebook to review the detailed analysis and visualizations.
2. **Virtual Poster**: View the `Virtual_Poster.pdf` for a summarized presentation of the project's findings and recommendations.
3. **Data Sources**: Ensure access to the necessary datasets as referenced in the notebook for replication or further analysis.

## Acknowledgments

- **Data Sources**:
  - NYC Traffic Crash Data: [NYC OpenData Motor Vehicle Collisions - Crashes]([https://opendata.cityofnewyork.us/](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data))
  - Weather Data: [NYC Weather - 2016 to 2022 (from Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/datasets/aadimator/nyc-weather-2016-to-2022?select=NYC_Weather_2016_2022.csv))
