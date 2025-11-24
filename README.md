# Data-Science-Public-Health-Analytics-Project
This repository contains a comprehensive data science project analyzing HIV burden, multidimensional poverty, and child mortality trends using global datasets from WHO, the World Bank, and the UN Inter-agency Group for Child Mortality Estimation.
The analysis focuses on long-term trends, regional disparities, and socioeconomic factors influencing health outcomes.

 Project Overview

This project investigates three major public health themes:

1. Global HIV Burden Analysis (2000–2023)

Analyzed WHO Global Health Observatory data for all countries from 2000–2023.

Visualized HIV trends for countries contributing to 75% of the global HIV burden.

Generated regional trend plots for WHO regions using the ParentLocationCode classification.

2. Linking HIV Burden With Multidimensional Poverty

Merged WHO HIV data with the World Bank Multidimensional Poverty Index (MPI).

Investigated socioeconomic indicators including:

Income

Education level, School enrollment, Access to electricity, Sanitation, Drinking water

Applied mixed-effects models (lme4) to account for random effects of country and year.

Interpreted relationships between poverty dimensions and HIV prevalence.

3. Under-Five & Neonatal Mortality in the East African Community

Filtered UN mortality datasets for EAC member countries.

Created geospatial visualizations using GADM shapefiles.

Mapped latest national estimates for:

Under-five mortality, Neonatal mortality, Produced trend plots showing:, Average regional trajectories, Country-level point estimates over time

Identified countries with the highest mortality levels.
