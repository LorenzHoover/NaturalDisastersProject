# US Weather Event Severity Analysis (1975–2024)

## Project Overview
This project analyzes historical weather events across the United States using machine learning and interactive geospatial visualization. The project utilizes logistic regression models, geospatial data, and climate indicators to explore the relationships between weather event severity, greenhouse gas emissions, and global temperature anomalies.

The accompanying Tableau dashboard allows users to interactively explore event severity by fatalities, injuries, damage, emissions, and temperature anomalies.

## Methodology
- Logistic Regression: Model trained on historical weather event data to classify events into severity classes.  
- Feature Engineering: Severity score created from fatalities, injuries, and log-transformed damage to reduce skew.  
- Class Balancing: SMOTE-ENN applied to handle class imbalances and improve model performance.  
- Data Wrangling: NOAA, NASA, and EPA data cleaned and merged into a master dataset.  
- Interactive Dashboard: Tableau dashboard with map-based event visualization and interactive controls.

## Dataset Summary
Data was sourced from NOAA, NASA, and the EPA. Key datasets include:
- NOAA Storm Event Data (1975–2024)  
- NASA Global Temperature Anomaly Data  
- EPA Per-Capita Greenhouse Gas Emissions Data

### Directory Structure
- Data: Cleaned datasets and original source files.  
- Models: Model training and experimentation notebooks.  
- Notebooks: Data wrangling and cleaning steps.  
- Dashboards: Tableau files for the interactive dashboard.

## Dashboard Links
- Interactive Tableau Dashboard: [View Here](https://public.tableau.com/views/NaturalWeatherDisasterSeverity1975-2024/Dashboard1)  
- GitHub Repository: [View Here](https://github.com/LorenzHoover/NaturalDisastersProject)

## Technical Tools
- Python (Pandas, NumPy, Scikit-Learn)  
- Jupyter Notebooks  
- Tableau Desktop / Tableau Public  
- Git / GitHub  

## Instructions to Run Locally
1. Clone the repository:  
   ```bash
   git clone https://github.com/LorenzHoover/NaturalDisastersProject.git
   ```
2. Navigate to the directory:  
   ```bash
   cd NaturalDisastersProject
   ```
3. Open the Jupyter notebooks for model training and data wrangling.  
4. Open the Tableau workbook (`Severity Workbook.twbx`) in Tableau Desktop.

Explore the impact of climate and severe weather events across the United States.
