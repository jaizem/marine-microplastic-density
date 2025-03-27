# Marine Microplastics Analysis

This project focuses on analyzing and visualizing marine microplastics data sourced from the NOAA NCEI (National Centers for Environmental Information) dataset. The aim is to better understand the distribution of microplastics across different regions and identify key patterns in sample locations and measurement densities.

## Overview

Using the NOAA NCEI microplastic sample dataset, the project involved several stages of data cleaning, statistical analysis, and geospatial visualization. The analysis aims to uncover insights related to microplastic pollution, particularly along coastal areas affected by ocean currents.

## Key Steps & Methodology

1. **Data Cleaning & Preparation**:  
   The dataset underwent extensive cleaning to ensure consistency and accuracy in the data. This process involved handling missing values, filtering out irrelevant records, and standardizing location data to prepare for further analysis.

2. **Correlation Analysis**:  
   Correlation tests were performed to examine potential relationships between sample location density and measurement density, helping to identify areas where high concentrations of microplastics are most prevalent.

3. **Geospatial Analysis**:  
   Using Geopandas, the data was visualized in a geospatial context to map the concentration density of microplastics. Kernel Density Estimation (KDE) was applied to highlight areas of high accumulation.

4. **Focus on the Pacific Ocean**:  
   The data was aggregated by location to zoom in on the Pacific Ocean, with a particular focus on the Mexico-Pacific coastline. This region is influenced by tidal currents that push residual microplastic accumulations from the Great Pacific Garbage Patch toward the shore.

5. **Sampling Method Analysis**:  
   The project also analyzed the most common sampling methods used in the dataset. Histograms were created to visualize the distribution of sample sizes and densities, providing insights into the extent of data collection in different regions.

6. **Visualization**:  
   Interactive maps were created using Geopandas and Contextily to add basemaps to the visualizations. These maps illustrate the distribution and density of microplastic samples across different regions and time periods.

## Tools & Libraries Used

- **Python**: The primary programming language for data manipulation, analysis, and visualization.
- **Geopandas**: Used for handling geospatial data and performing geospatial analysis.
- **Kernel Density Estimation (KDE)**: Applied to estimate the density of microplastic samples in specific regions.
- **Contextily**: Integrated basemaps into the visualizations to provide geographic context.
- **Matplotlib/Seaborn**: Used for creating histograms and other visualizations of the data.

## Results & Insights

- Identification of regions with the highest microplastic concentrations, particularly along the Mexico-Pacific coastline.
- Insights into the most common sampling methods and how they correlate with sample size and density.
- Clear visual representation of microplastic concentration across time and space.

## Future Work

- Expanding the analysis to other regions and comparing microplastic concentration trends globally.
- Enhancing the correlation analysis to explore other factors influencing microplastic concentrations, such as ocean currents and plastic type.
