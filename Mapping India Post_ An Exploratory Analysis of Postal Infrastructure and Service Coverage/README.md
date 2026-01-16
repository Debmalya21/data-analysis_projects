# Mapping India Post: An Exploratory Analysis of Postal Infrastructure and Service Coverage

## Project Overview
This project explores the structure, distribution, and service coverage of post offices across India using a dataset containing post office names, types, delivery capability, locations (districts, states, divisions, latitude/longitude), and administrative hierarchy.

The analysis was conducted at multiple levels:

1. **State-level:** Distribution of post offices across states and their share of the total network.  
2. **Circle–Region–Division-level:** Administrative hierarchy and regional coverage analysis.  
3. **Office Type & Service Coverage:** Prevalence of Branch Offices (BOs), Post Offices (POs), Head Offices (HOs), and delivery vs non-delivery capabilities.  
4. **Geographic Patterns:** Mapping offices to analyze spatial distribution across India.  
5. **District-level Micro Analysis:** Identifying top and bottom districts by office count and delivery coverage.  
6. **Case Study — Bankura, West Bengal:** Division-level and district-level micro-analysis including office types, delivery coverage, and geographic spread.

Python libraries used: **Pandas, NumPy, Matplotlib, Seaborn, Squarify**.

## Dataset Description: 

## Dataset Source: https://catalog.data.gov/dataset/electric-vehicle-population-data
### Key Columns:
       'circlename', 'regionname', 'divisionname', 'officename', 'pincode',
       'officetype', 'delivery', 'district', 'statename', 'latitude',
       'longitude'

Dataset Characteristics
Total entries: 165627

 Data Source : Open Government Data (OGD) Platform India
            (https://data.gov.in)
## Key Findings

### 1. State-Level Distribution
- Uttar Pradesh has the **highest number of post offices**, followed by Maharashtra and Tamil Nadu.  
- Smaller states and Union Territories (e.g., Lakshadweep, Chandigarh, Puducherry) have very few offices.  
- The **top ten states together account for more than half of all post offices**, showing concentration in populous or large states.

### 2. Circle–Region–Division Hierarchy
- Circles vary in administrative complexity; large circles manage multiple regions and divisions, while smaller circles rely on **centralized reporting**.  
- Administrative hierarchy influences **regional office distribution** and density.

### 3. Office Type & Service Coverage
- Branch Offices (BOs) dominate the network, indicating strong **rural outreach**.  
- Post Offices (POs) and Head Offices (HOs) are concentrated in urban or administrative hubs.  
- **Delivery services are widely available**, though urban districts like Delhi show higher proportions of non-delivery offices.

### 4. Geographic Patterns
- Offices are generally **well-distributed geographically**, reflecting planning for accessibility.  
- Larger states have a **wider spatial footprint**, while smaller/compact states have tighter clustering.  
- Remote areas show sparse coverage, highlighting geographic and population constraints.

### 5. District-Level Insights
- High-density districts (e.g., Y.S.R., Pune, 24 Parganas South) have the most offices due to large populations or areas.  
- Remote or island districts (e.g., Lakshadweep, Arunachal Pradesh districts, Mizoram districts) have minimal post office presence.  
- Urban districts often exhibit **lower delivery ratios**, reflecting non-delivery administrative offices.

### 6. Bankura Case Study
- Bankura district ranks **7th in West Bengal** by post office count with **488 offices** concentrated in Bankura Division.  
- Office type composition is **heavily BO-dominated**, with minimal PO and HO presence.  
- **Delivery coverage is very high (97.8%)**, exceeding the West Bengal state average (92.4%).  
- Offices are **evenly geographically distributed**, with a few outliers in remote areas.

---

## Overall Conclusion
- **India Post infrastructure is focused on populous and rural regions**, with Branch Offices forming the backbone.  
- **Delivery services are widely implemented**, though urban administrative districts have relatively more non-delivery offices.  
- Circles and divisions follow **centralized or decentralized models** depending on region.  
- Micro-analysis (Bankura) shows **strong last-mile service penetration** and effective geographic coverage.  
- Insights can inform **policy planning, expansion of services, and addressing regional infrastructure imbalances**.

---


## Tools & Libraries
- **Python 3**  
- **Pandas, NumPy** — Data manipulation  
- **Matplotlib, Seaborn** — Visualization  
- **Squarify** — Treemap visualizations  

---

## License
This project is for educational and portfolio purposes. Dataset attribution: **India Post Office data**.

