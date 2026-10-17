# data-science-project
# Macao Housing‑Affordability Analysis (2013‑2025)

## Problem / Research Question
[This project aims to answer the question: "Is the growth of housing prices in Macao faster than the growth of residents' income? If so, by how much is the gap?"]

## Dataset
| Source | Description | Usage permission |
|--------|-------------|------------------|
 DSEC（Statistics and Census Service of Macao） | Residential Property Price Index (annual) | Public Government Portal, free for academic/teaching purposes |
| DSEC – Median monthly employment earnings | Average monthly income of residents in each year | Same as above |
| DSEC – Consumer Price Index (Optional) | Price index for inflation adjustment | Same as above | 

## Methods & Tools
- Programming language / Environment 
- Key library（pandas、numpy、matplotlib、seaborn、scikit‑learn ...）  
- Main steps (data acquisition → cleaning → alignment → re-basement → calculating growth rate → visualization)

## Key Findings
- 发现 1：[The RPPI has increased from 100 to 210, representing a cumulative growth of 110%.]
- 发现 2：[The annual income has only increased by 50%.] 

## Limitation
- Data availability (such as the absence of regional income data)  
- Only using nominal values, without making any adjustments for the real value due to inflation  
- The result is merely descriptive and makes no assertion regarding causality. 

## How to Run
1. **Clone repository**  
   ```bash
   git clone https://github.com/<MC661505>/data‑science‑project.git
   cd data‑science‑project**
