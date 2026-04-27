# Psychological Distress and Alcohol Use: Variation by Sex and Income Level

## Overview

This project examines how psychological distress is associated with alcohol use, and whether these patterns differ by sex and income level using the 2024 National Survey on Drug Use and Health (NSDUH) dataset.

## Data Source

The data come from the publicly available Substance Abuse and Mental Health Services Administration (SAMHSA) National Survey on Drug Use and Health 2024 dataset:

<https://www.samhsa.gov/data/data-we-collect/nsduh-national-survey-drug-use-and-health/datafiles>

NSDUH is a nationally representative, cross-sectional survey of the U.S. civilian, noninstitutionalized population aged 12 and older. 

## Directory Structure

DATA555_final/

final-4a.Rmd - Main dashboard file/source codes

README.md

data/NSDUH_2024 - Dataset 

The output will be rendered into the main folder of DATA555_final. 

## Interactive Visualizations

This dashboard utilizes plotly to provide dynamic insights into the NSDUH dataset.

### Hover Tootips
Hover over points or bars to view detailed information, including alcohol use days, psychological distress scores, group averages, and sample sizes.

### Zoom and Pan
Click and drag to zoom into specific regions of the scatterplot. Double-click to reset the view.

### Legend Interaction (Scatterplot)
Click on legend items (i.e. Male/Female) to show or hide specific groups for clearer comparison.

### Detailed Summary Information (Bar Chart)  
Hover over each bar to view mean alcohol use, confidence intervals, number of respondents, and the ANOVA p-value.

These features allow users to explore patterns more closely and better understand relationships within the data beyond the static view.

## Real-world importance and impact
This dashboard shows that alcohol use is associated with psychological distress and that differences across income levels are statistically significant (ANOVA p < 0.05). These findings can inform targeted public health strategies, though further modeling is needed to understand the direction and drivers of these differences.
