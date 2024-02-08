![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![GitHub Releases](https://img.shields.io/badge/available-syntax-blue)


# Sanofi Data Challenge

This is the LSHTM MSc Health Data Science-Sanofi for Data Challenge project

## Description
This project want to capture the pre and post COVID-19 RSV and sesonal Flu pattern for Northern and Southern Hemisphere countries 

## Project items
### Dataset
All of the datasets that using in this project. The main data of this project consist of:
- `Consolidated_dataset_MASTER.xlsx` = dataset consolidation for Flu and RSV timeseries data 2017-2023 from France, Brazil, England, Australia, US, and Turkey

### Output
All of the output for the report and presentation including 
- graphs in `graphs`
- tables in `tables` 

### R Script
All of the R script that use for produce the output in the report and presentation. First 5 characters of files name are codes for regions/countries 
- The global data =  `01`
- England = `02`
- France = `03`
- Turkey = `04`
- USA = `05`
- Australia = `06`
- Brazil = `07`

## Data and Scrapping
### Data Source
- FluNet and FluID from [WHO](https://www.who.int/teams/global-influenza-programme/surveillance-and-monitoring/influenza-surveillance-outputs)
- England = [National Flu and COVID-19 surveillance reports](https://www.gov.uk/government/collections/weekly-national-flu-reports)
- France = [Bulletin épidémiologique grippe and Bulletin IRA](https://www.santepubliquefrance.fr)
- Turkey = [Haftalık İnfluenza Raporları ](https://grip.saglik.gov.tr/tr/haftalik-influenza-raporu)
- USA = [CDC RESP-NET](https://www.cdc.gov/surveillance/resp-net/dashboard.html)
- Australia = [Australian Influenza Surveillance Reports ](https://www.health.gov.au/resources/collections/australian-influenza-surveillance-reports-2023)
- Brazil = [OpenDataSUS](https://opendatasus.saude.gov.br)

### Scrapping Method
- [Digitizer](https://apps.automeris.io/wpd/)




