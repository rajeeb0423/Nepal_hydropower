# Nepal Hydropower Projects Visualization

This repository provides a comprehensive workflow for visualizing hydropower projects in Nepal using Tableau. It covers data cleaning using Python, geospatial mapping, and interactive dashboard creation.

## Overview

- **Data Cleaning:** Python (Pandas, GeoPandas)
- **Visualization:** Tableau
- **Datasets:**
  - [Hydropower Projects of Nepal](https://opendatanepal.com/dataset/hydropower-projects-of-nepal): Information on hydropower projects (operational, under construction, planned).
  - [Nepal Administrative Boundary Shapefile](https://download.hermes.com.np/nepal-administrative-boundary-wgs/): Shapefile for Nepal’s administrative regions, used for mapping.

## Workflow

1. **Data Acquisition**
   - Download project and boundary datasets from the links above.

2. **Data Cleaning & Preparation**
   - Data cleaning was performed in Python using `pandas` and `geopandas` libraries. The steps are:
     - Clean and filter hydropower project data.
     - Clean the  shapefile data for mapping.
     - Merge datasets as needed for geospatial analysis (either in Python or Tableau).

3. **Visualization in Tableau**
   - Import cleaned datasets into Tableau.
   - Create interactive dashboards visualizing hydropower projects geographically and by project status.

## Dashboard

You can view an image of the interactive Tableau dashboard below. Click the image to go to Tableau public and see the interactive version:

[<img src="https://github.com/rajeeb0423/Nepal_hydropower/blob/main/Hydropower_dashboard.png" alt="Hydropower Dashboard" width="800">](https://public.tableau.com/views/NepalHydropower/HydropowerDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Requirements

- Python 3.x
- pandas
- geopandas
- Tableau (desktop or public version)

## License

This project is open source and available under the [MIT License](LICENSE).
