# ili_surveillance_kenya
## Analyzing Regional Trends in Influenza-Like Illness (ILI) in Kenya: A Quantitative Epidemiology Case Study (Center for Epidemiological Modeling and Analysis)
The project analyzed influenza-like illnesses across various regions/counties in Kenya between 2023 and 2024 for informed public health survillance and well-informed IPC interventions.

### 1. Background
As an initial task at the Centre for Epidemiological Modeling and Analysis (CEMA), you are presented with a dataset from an epidemiological research project, "Analyzing Regional Trends in Influenza-Like Illness (ILI) in Kenya: A Quantitative Epidemiology Case Study." The study collected data on year (2023-2024), the epidemiological week (epi_week), county, age categories (age_group), percentage of outpatient visits due to ILI (ili_percentage), and the estimated population for that age group in that county (population). The objective is to evaluate temporal and county-specific ILI trends and interpret the findings to inform public health decisions.

### 2. Data
– Raw Excel workbook containing all sheets:
[data/Epi_Task_Data.csv](data/Epi_Task_Data.csv)

#### Data Sample
|   year |   epi_week | county   | age_group   |   ili_percentage |   population |
|-------:|-----------:|:---------|:------------|-----------------:|-------------:|
|   2023 |          1 | Nairobi  | 0-4yrs      |              6.1 |         3452 |
|   2024 |          1 | Nairobi  | 0-4yrs      |              3.2 |         3658 |
|   2023 |          2 | Nairobi  | 0-4yrs      |              4.5 |         3043 |
|   2024 |          2 | Nairobi  | 0-4yrs      |              4.9 |         2765 |
|   2023 |          3 | Nairobi  | 0-4yrs      |              4.6 |         6975 |
|   2024 |          3 | Nairobi  | 0-4yrs      |              3.8 |          609 |
|   2023 |          4 | Nairobi  | 0-4yrs      |              6.3 |         1642 |
|   2024 |          4 | Nairobi  | 0-4yrs      |              3.9 |         1118 |
|   2023 |          5 | Nairobi  | 0-4yrs      |              7   |         9418 |
|   2024 |          5 | Nairobi  | 0-4yrs      |              3.9 |          526 |
|   2023 |          1 | Mombasa  | 0-4yrs      |              6   |         9283 |
|   2024 |          1 | Mombasa  | 0-4yrs      |              7.4 |         1633 |
|   2023 |          2 | Mombasa  | 0-4yrs      |              1.9 |         2252 |
|   2024 |          2 | Mombasa  | 0-4yrs      |              3.6 |         7567 |
|   2023 |          3 | Mombasa  | 0-4yrs      |              3.8 |         5122 |
|   2024 |          3 | Mombasa  | 0-4yrs      |              5   |         4862 |

### 3. Task process
##### a)	Descriptive analysis
- i.	Computing a table showing the mean ILI percentage per county per year.
- ii.	Plotting ILI weekly trend, identifying the peak ILI weeks across counties and describing the seasonal pattern of ILI cases.
##### b)	Computing epidemiological measures
- i.	Calculating the incidence rates per 100,000 population across three counties.
- ii.	Using a correlation to compare ILI percentages across any three counties.

### 4. Findings

### 5. Project Notebook
Explore the full analysis in the Jupyter notebook:  
[Melanie_Omondi_CEMA_Epidemiology_Task.ipynb](ili_surveillance_kenya/notebook/Melanie_Omondi_CEMA_Epidemiology_Task.ipynb)

➡ View rendered version on [nbviewer](https://nbviewer.org/github/<Melanie331>/<ili_surveillance_kenya>/blob/main/ili_surveillance_kenya/notebook/Melanie_Omondi_CEMA_Epidemiology_Task.ipynb)

![Open in nbviewer](https://img.shields.io/badge/Open%20in-nbviewer-blue?style=flat-square)



