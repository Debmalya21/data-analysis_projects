# Project Title

## Spatio-Temporal Analysis of Urban Crime Patterns

# Motivation
Understanding when and where crimes occur is essential for effective urban planning, public safety, and resource allocation. This project aims to uncover meaningful patterns in crime behavior by jointly analyzing time, space, and crime types, rather than treating them in isolation.

# Dataset Description

Multi-year urban crime records

Includes:
Data columns (total 28 columns):
 #   Column          Non-Null Count    Dtype  
---  ------          --------------    -----  
 0   dr_no           1004991 non-null  int64  
 1   date_rptd       1004991 non-null  object 
 2   date_occ        1004991 non-null  object 
 3   time_occ        1004991 non-null  int64  
 4   area            1004991 non-null  int64  
 5   area_name       1004991 non-null  object 
 6   rpt_dist_no     1004991 non-null  int64  
 7   part_1-2        1004991 non-null  int64  
 8   crm_cd          1004991 non-null  int64  
 9   crm_cd_desc     1004991 non-null  object 
 10  mocodes         853372 non-null   object 
 11  vict_age        1004991 non-null  int64  
 12  vict_sex        860347 non-null   object 
 13  vict_descent    860335 non-null   object 
 14  premis_cd       1004975 non-null  float64
 15  premis_desc     1004403 non-null  object 
 16  weapon_used_cd  327247 non-null   float64
 17  weapon_desc     327247 non-null   object 
 18  status          1004990 non-null  object 
 19  status_desc     1004991 non-null  object 
 20  crm_cd_1        1004980 non-null  float64
 21  crm_cd_2        69160 non-null    float64
 22  crm_cd_3        2314 non-null     float64
 23  crm_cd_4        64 non-null       float64
 24  location        1004991 non-null  object 
 25  cross_street    154236 non-null   object 
 26  lat             1004991 non-null  float64
 27  lon             1004991 non-null  float64
 ### Number of Rows- 1004991
 ### Number of Columns - 28
 ### Data Source - data.gov (An official website of the United States government)
 
# Analysis Workflow

- Temporal Analysis

- Yearly trends and cumulative growth

- Monthly seasonality

- Reporting delays

- Hourly and weekday crime patterns

- Spatial Analysis

- Crime counts by area

- Area-wise crime-type heatmaps

-  percentage comparisons

- Geospatial Visualization

- Latitude–longitude scatterplots

- Area-based hue overlays

- Hexbin hotspot detection

- Location-Level Investigation

- Top crime locations

- Location vs crime-type heatmaps

## Visualizations Used

- Line plots (trends, cumulative counts)

- Bar charts (area and location comparisons)

- Heatmaps (crime-type specialization)

- Scatterplots (geographic dispersion)

- Hexbin plots (hotspot density)

- Each visualization is paired with explicit insights, not just descriptive statistics.

## Key Insights

- Crime follows strong daily and seasonal rhythms

- Urban core areas dominate crime volume

- High-crime divisions exhibit similar internal crime compositions

- Crime hotspots are localized and persistent

- Crime types vary systematically by land-use and location function

## Tools & Libraries

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

## Future Improvements

- Incorporate population or footfall normalization

- Add temporal forecasting models

- Integrate socioeconomic or land-use data

- Apply spatial clustering algorithms (DBSCAN, KDE)