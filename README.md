# Data for "Human Health: Measuring the impact of rising temperatures on mortality to target adaptation planning" (March 2026)

The following data files contain data underlying the Climate Impact Lab Adaptation Roadmap Report, March 2026: 
**_Human Health: Measuring the impact of rising temperatures on mortality to target adaptation planning_**


For more about the report, see [here](https://impactlab.org/research/human-health-measuring-the-impact-of-rising-temperatures-on-mortality-to-target-adaptation-planning/). Click [here](https://impactlab.org/wp-content/uploads/2026/03/CIL_MortalityReport_2026.pdf) to download the report.


The Climate Impact Lab makes data publicly available under the CC BY 4.0 license.

## Data Summary:
Data is based on the methods summarized in Carleton et al. (2022). The data are the impacts of climate change on mortality rates in 2050 (i.e., 20-year average of annual impacts (2040-2059)) under an emissions trajectory consistent with 3°C of warming by the end of the century. (The 3°C warming level represents an increase in Global mean Surface Air Temperature (GSAT) of 3°C at 2100 relative to a pre-industrial time period (1850-1900).) Mortality projections are based on Shared Socioeconomic Pathway 2 (SSP2 v1.1, IIASA), which includes population and GDP into the future, and account for adaptation due to income growth. 

## Data files
1. CIL_HumanHealth_March2026-region_data.csv
2. CIL_HumanHealth_March2026-country_data.csv

### 1. CIL_HumanHealth_March2026-region_data.csv
Mean change in net mortality rate for all Impact Regions.

#### Data fields:
- `region_id` - Unique Impact Region identifier 
  - Description: The first three digits of the identifier align to the 3-digit ISO code for the country in which the region is based (ISO 3166-1 alpha-3). There are 24,378 Impact Regions across the globe.
- `mean` - Mean change in net mortality rate.
  - Unit: deaths / 100,000 people
  - Description: Mean change in net mortality rate due to climate-change driven changes in temperature across all age groups. Negative values represent a net decrease in temperature-related mortality (i.e., beneficial impacts). Positive values indicate a net increase in temperature-related mortality (i.e., detrimental impacts).
- `region_name` - Name of Impact Region
  - Description: Name of the impact region, which is based on ADM2 names.


### 2. CIL_HumanHealth_March2026-country_data.csv
Population-weighted average of mean change in net mortality rate for all Impact Regions in specified countries. Populations are based on the SSP2 v1.1 IIASA projections for 2050.

#### Data fields:
- `Code` - 3 digit ISO country code
- `mean` - Population-weighted average of mean change in net mortality rate for all Impact Regions within country borders.

----
## References
Carleton, Tamma, et al. “Valuing the Global Mortality Consequences of Climate Change Accounting for Adaptation Costs and Benefits.” The Quarterly Journal of Economics 137(4), 2037–2105 (2022). https://doi.org/10.1093/qje/qjac020


Rode, Ashwin, et al. “Estimating a Social Cost of Carbon for Global Energy Consumption.” Nature 598, 308–314 (2021). https://doi.org/10.1038/s41586-021-03883-8
