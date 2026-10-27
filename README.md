# UK Road Accident Analysis (2019 - 2025)

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) and temporal trend analysis on road traffic accidents in the United Kingdom (UK) from 2019 to 2025. By analyzing environmental factors, road conditions, and vehicle types, this project identifies key risk patterns to support data-driven decision-making for road safety.

## 🎯 Problem Statement
The high frequency of road accidents significantly impacts public safety and infrastructure. The key analytical questions addressed in this project include:
1. **Temporal Trends:** How have the frequency and severity of traffic accidents evolved from 2019 through 2025?
2. **Environmental Factors:** To what extent do weather, road surface conditions, and lighting affect accident severity?
3. **Vehicle Factors:** Which vehicle types are most frequently involved in traffic incidents?
4. **Geographic Distribution:** Which districts experience the highest concentration of accidents and casualties?

## 📊 Dataset Description
The dataset is sourced from Kaggle and covers recorded road traffic accidents across the UK:
- **Timeframe:** 2019 – 2025
- **Data Volume:** 670,679 rows and 14 columns
- **Coverage:** 422 district areas and 910,120 casualties
- **License:** MIT License
- **Data Source:** [Accident Analysis Dataset on Kaggle](https://www.kaggle.com/datasets/deeplumiere/accident-analysis-dataset)

## 📊 Coloumn Description
- Index: A unique identification number or reference number for each traffic accident record.
- Accident_Severity: The severity level of the accident 
- Accident Date: The date when the traffic accident occurred 
- Latitude: The geographical latitude coordinate of the accident location 
- Light_Conditions: The lighting conditions at the time of the accident
- District Area: The name of the district or area where the accident took place 
- Longitude: The geographical longitude coordinate of the accident location 
- Number_of_Casualties: The total number of casualties or people injured as a result of the accident.
- Number_of_Vehicles: The total number of vehicles involved in the accident.
- Road_Surface_Conditions: The condition of the road surface at the time of the incident 
- Road_Type: The type or configuration of the road where the accident occurred 
- Urban_or_Rural_Area: The classification of whether the location is in an urban area (Urban) or a rural area (Rural).
- Weather_Conditions: The weather conditions during the accident 
- Vehicle_Type: The type of vehicle involved 

> **Note:** In compliance with licensing and GitHub storage best practices, the raw data file is not hosted in this repository. Please download the original dataset directly from the Kaggle link above.

## 🛠️ Methodology & Analytical Workflow
The analytical pipeline follows these structured steps:
1. **Data Cleaning & Preprocessing:**
   - Handling missing values and parsing temporal data types (dates and timestamps).
   - Validating and encoding categorical variables.
2. **Exploratory Data Analysis (EDA):**
   - Univariate and bivariate analysis to evaluate key variable distributions.
   - Assessing the relationship between weather/lighting conditions and casualty severity.
3. **Geospatial & District Aggregation:**
   - Aggregating metrics across 422 districts to highlight high-risk accident hotspots.
4. **Data Visualization:**
   - Building annual trend charts, temporal heatmaps, and vehicle distribution plots using `matplotlib` and `seaborn`.

## 📂 Repository Structure
```text
.
├── .gitignore                  # Prevents temporary Python/Colab files from being tracked
├── LICENSE                     # MIT License
├── README.md                   # Main project documentation
└── Accident_Analysis.ipynb     # Primary analytical notebook (Google Colab)
