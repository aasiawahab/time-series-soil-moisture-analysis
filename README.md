# Time Series Analysis of ERA5LAND and ASCAT Soil Moisture Data  

This repository contains a comprehensive analysis of soil moisture data from ERA5LAND and ASCAT, focusing on time-series analysis to explore trends, patterns, and correlations. The project uses Python for data processing, visualization, and statistical analysis.  

## Features  
- **Data Import and Preprocessing**:  
  - Handling soil moisture datasets from ERA5LAND and ASCAT.  
  - Cleaning, transforming, and aligning datasets for analysis.  

- **Exploratory Data Analysis (EDA)**:  
  - Summarizing key variables such as temperature, precipitation, and soil moisture levels.  
  - Visualizing spatial and temporal distributions.  

- **Time Series Analysis**:  
  - Investigating soil moisture trends over time.  
  - Correlation analysis between soil moisture, temperature, and precipitation.  

- **Visualization**:  
  - Interactive and static plots to explore data patterns.  
  - Comparing ERA5LAND and ASCAT datasets across time and regions.  

## Data Description  
### ERA5LAND  
ERA5LAND provides data with the following key variables:  
- `time`: Time of observation.  
- `lon`: Longitude.  
- `lat`: Latitude.  
- `alt`: Altitude.  
- `t2m`: Temperature at 2 meters.  
- `stl1`: Soil temperature (Level 1).  
- `tp`: Total precipitation.  
- `swvl1`: Volumetric soil water layer.  

### ASCAT  
ASCAT soil moisture data includes:  
- Surface soil moisture values.  
- Metadata for geospatial alignment.  

## Technologies Used  
- **Python**: Programming language for analysis.  
- **Libraries**:  
  - `Pandas` and `NumPy`: Data manipulation and transformation.  
  - `Matplotlib` and `Seaborn`: Visualization.  
  - `NetCDF4` and `xarray`: Handling NetCDF files.  

## How to Use  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/aasiawahab/time-series-soil-moisture-analysis.git  
2. Follow the steps detailed in the notebook to reproduce the analysis.

## Key Insights
- Temporal trends in soil moisture levels across regions.
- Relationships between soil moisture, temperature, and precipitation.
- Visual comparisons of soil moisture data from ERA5LAND and ASCAT.

## License
This project is licensed under the MIT License.

## Contact
For questions or feedback, please contact me at aasiawahab92@gmail.com .
