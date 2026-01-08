# Electric Vehicle Adoption and Policy Insights: Washington State EV Landscape Analysis
## Project Overview
This project analyzes electric vehicle (EV) registrations in Washington State, covering over 270,000 vehicles. The goal is to uncover market trends, manufacturer and model dominance, geographic adoption patterns, policy alignment, and electric range reporting quality. Insights from this project are useful for policymakers, urban planners, EV infrastructure developers, and market analysts.
All analysis is performed using Python, Pandas, Matplotlib, and Seaborn.
## Objectives
- Trend Analysis: Examine how EV adoption has changed over model years, distinguishing Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).
- Manufacturer & Model Insights: Identify market leaders and top models to reveal competitive dynamics.
- Geographic Patterns: Explore county- and city-level adoption to highlight urban dominance and regional disparities.
- - Policy Lens: Analyze Clean Alternative Fuel Vehicle (CAFV) eligibility across EV types.
- Electric Range Assessment: Evaluate electric range reporting quality and trends across model years.
- Actionable Insights: Provide clear findings that can guide decision-making, policy development, and market strategies.
## Dataset Description: 
Dataset Description
The dataset used in this project contains electric vehicle (EV) registration records for Washington State. It includes over 270,000 entries, with each row representing a unique EV. The dataset captures vehicle specifications, registration details, geographic information, and policy-related attributes, allowing for comprehensive analysis of EV adoption trends.
## Dataset Source: https://catalog.data.gov/dataset/electric-vehicle-population-data
### Key Columns:
       'VIN (1-10)', 'County', 'City', 'State', 'Postal Code', 'Model Year',
       'Make', 'Model', 'Electric Vehicle Type',
       'Clean Alternative Fuel Vehicle (CAFV) Eligibility', 'Electric Range',
       'Legislative District', 'DOL Vehicle ID', 'Vehicle Location',
       'Electric Utility', '2020 Census Tract'

Dataset Characteristics
Total entries: 270262
EV types: BEV and PHEV
Missing values: Some electric range and CAFV eligibility entries are missing or unknown
Geographic granularity: County, city, and census tract level
This dataset allows for analysis of EV market trends, manufacturer/model dominance, geographic adoption, policy alignment, and electric range reporting quality.
 Data Source : DATA.GOV
(An official website of the United States government)
## Key Findings
### 1. EV Adoption Trends
EV adoption accelerated sharply post-2017, dominated by BEVs.
PHEVs emerged around 2010 and grew modestly, showing a transitional adoption pathway.
Overall, the market shows a clear shift toward fully electric vehicles.
### 2. Manufacturer Dominance
Tesla is the leading manufacturer, far ahead of others individually.
Chevrolet, Nissan, and other manufacturers contribute meaningfully but remain far behind Tesla.
Collectively, smaller brands maintain a fragmented long-tail market.
### 3. Model Dominance
Tesla models Model Y and Model 3 dominate registrations.
Non-Tesla models such as Leaf and Bolt EV trail by a wide margin.
EV adoption is concentrated among a small number of high-demand models.
### 4. Geographic Adoption Patterns
King County accounts for nearly half of all EV registrations, with Seattle as the primary city hub.
Other counties and cities have significantly lower adoption, reflecting urban-centric growth.
### 5. Policy Insights (CAFV Eligibility)
BEVs are largely CAFV-eligible, while PHEVs show mixed eligibility.
A substantial number of BEV records have unknown eligibility, highlighting data reporting gaps.
### 6. Electric Range Reporting
Reporting is near 100% complete until 2020, showing reliable electric range data.
Post-2020, reporting quality drops sharply, cautioning against interpreting recent averages.
Average reported range for BEVs shows steady improvement until 2020.
## Conclusions
- The EV market is dominated by BEVs and Tesla, both at manufacturer and model levels.
- Urban centers, especially Seattle and King County, drive adoption, highlighting infrastructure and policy influence.
- Policy incentives (CAFV eligibility) align strongly with BEVs, while PHEVs are more variable.
- Data completeness and reporting quality should be considered when analyzing recent model years.
This project provides actionable insights into market trends, policy alignment, and adoption patterns, suitable for stakeholders in EV strategy, urban planning, and environmental policy.
## Technologies Used
Python (Pandas, NumPy) for data cleaning and aggregation
Matplotlib & Seaborn for visualizations