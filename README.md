**AnnArborWeatherData**
This repository contains a comprehensive analysis of temperature data from Ann Arbor, Michigan, focusing on the year 2015. Utilizing NOAA data, the project includes visualizations of record high and low temperatures, alongside weather station locations. 

**Temperature Analysis Project**

**Overview****
This repository contains a Jupyter Notebook that performs a temperature analysis for weather stations near Ann Arbor, Michigan, using NOAA data. The analysis includes visualizing record high and low temperatures from 2005 to 2014 and identifying record-breaking temperatures in 2015.

**Project Objectives**
- Plot the record high and low temperatures for each day of the year (excluding leap days) from 2005 to 2014.
- Overlay record-breaking temperatures from 2015 on the historical data.
- Visualize the locations of weather stations near Ann Arbor, Michigan.

**Data Sources**
- **Temperature Data**: NOAA data containing daily temperature records.
- **Station Data**: Information about weather stations, including their geographical coordinates.

**Libraries Used**
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization.
- `geopandas`: For geographical data handling and visualization.

**Analysis Steps**
1. **Data Loading**:
   - Load temperature and station data from CSV files stored in Google Drive.
  
2. **Data Preprocessing**:
   - Convert date columns to datetime objects.
   - Filter data for the years 2005 to 2014 and 2015.

3. **Record Highs and Lows Calculation**:
   - Calculate daily record highs (TMAX) and lows (TMIN) for each day of the year, excluding leap days.

4. **Visualization**:
   - Plot record high and low temperatures from 2005 to 2014.
   - Identify and overlay record-breaking temperatures from 2015.
   - Visualize the locations of weather stations near Ann Arbor.

**How to Run**
1. Clone the repository:
   ```bash
   git clone <repository_url>
