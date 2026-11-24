# Drought and Heat Shape Carnivore Movement and Human–Wildlife Conflict

This repository contains the processed data and R code supporting a study investigating how drought and extreme heat influence large carnivore settlement visitation and reported human–wildlife conflict in northern Botswana's Okavango Delta.

The study examines GPS tracking data from African wild dogs, lions, leopards, and cheetahs, alongside government Problem Animal Control (PAC) records of human–carnivore conflict.

## Repository contents

**`GPS and PAC Analysis_For Submission.Rmd`**

R Markdown script containing the statistical analyses, model diagnostics, and code used to generate the figures and supplementary analyses presented in the manuscript.

**Data files**

- `settlement_visits_final_dataset_monthly_nozeros.csv`: Monthly carnivore settlement visitation data and associated covariates.
- `settlement_visits_final_dataset_monthly_nozeros_diel.csv`: Settlement visitation data separated into light and dark periods.
- `results_settlement_visits`: Detailed settlement visitation records used for the hourly activity analysis.
- `pac_monthly_processed_ngamiland.csv`: Monthly carnivore conflict data for Ngamiland.
- `pac_monthly_processed_alldata.csv`: Monthly conflict data across the broader study region.
- `damage_summary.csv`: Aggregated conflict incidents by damage category and carnivore species.
- `spi_rainfall_dog_camp.csv`: Standardized Precipitation Index data.
- `Temperature_Hourly_Era5.csv`: ERA5 temperature data.
- `Settlement_Data.csv`: Settlement characteristics and locations.

## Running the analysis

The analyses were conducted in R using the packages listed at the beginning of the R Markdown file.

Some spatial figures require downloading geographic boundaries or satellite imagery and therefore require an internet connection.

## Data availability and limitations

The full carnivore GPS location dataset (all_locations) and individual settlement visitation records (results_settlement_visits) are not included in this public repository due to the sensitivity of wildlife location data. Both datasets are retained separately.

Consequently, some analyses and figures requiring individual GPS coordinates or settlement entry records cannot be reproduced from the publicly available files alone. The remaining processed datasets and code are provided to support transparency and reproducibility of the analyses.

## Citation and archived version

The data and code associated with this manuscript are permanently archived on Zenodo:

West et al. (2026). Drought and heat shape carnivore movement and human–wildlife conflict: Manuscript data and code, v1.0.0. Zenodo. https://doi.org/10.5281/zenodo.24490305

