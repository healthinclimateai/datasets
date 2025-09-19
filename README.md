# Climate and Health Datasets Collection

This repository contains datasets for climate and health research, focusing on the intersection of environmental factors and healthcare outcomes. The datasets are organized into several categories from different sources and partners.

## Dataset Overview

### Apollo Hospitals (`apollo_hospitals/`)
**Source**: Apollo Hospitals
**Description**: Synthetic clinical data for COPD (Chronic Obstructive Pulmonary Disease) research
- `copd_generated_data 2.xlsx` - Synthetic data on 8,000 COPD patients (2021-2024)
- `Methodology for Developing Synthetic Clinical Data 1 2.docx` - Documentation on synthetic data generation methodology
- **Years Covered**: 2021-2024

### Climate Care Consulting (`climate_care_consulting/`)
**Source**: Climate Care Consulting
**Description**: Emissions and energy use reporting data
- `Emissions Energy Use Reporting Dataverse.xlsx` - Environmental emissions and energy consumption data
- **Purpose**: Analysis of carbon footprint and energy efficiency in healthcare settings

### Milliman (`milliman/`)
**Source**: Milliman
**Description**: Air quality, temperature, and healthcare utilization data for California
- `CA_aqi.csv` - California Air Quality Index data (70MB+)
- `CA_max_daily_temps.csv` - California maximum daily temperature data (29MB+)
- `FIPS to AreaID crosswalk.csv` - Geographic mapping between FIPS codes and Area IDs
- `healthcare utilization summary data.xlsx` - Healthcare utilization patterns
- **Years Covered**: 2017-2019
- **Geographic Scope**: California
- **Content**: Air pollution, heat, and socioeconomic data correlation with healthcare outcomes

### Practice Greenhealth (`practice_greenhealth/`)
**Source**: Practice Greenhealth
**Description**: Healthcare sustainability and environmental performance data
- `2014-2024 Practice Greenhealth Data Export_CIA Hackathon 2025.xlsx` - Comprehensive sustainability metrics
- `2014-2024 Practice Greenhealth Data Export_CIA Hackathon 2025_pt2.xlsx` - Additional sustainability data
- **Years Covered**: 2014-2024
- **Purpose**: Healthcare facility environmental impact assessment and sustainability tracking

### System (`system/`)
**Source**: System Research Platform
**Description**: Climate-related research findings and relationships
- `System API Notebook (Cornell Climate Week Hackathon).ipynb` - Jupyter notebook for API access and analysis
- `system_climate_findings.csv` - Climate research findings data (4MB+)
- `system_climate_relationships.csv` - Climate data relationships and correlations (800KB+)
- `system_climate_topics.csv` - Climate research topics taxonomy
- **Purpose**: Systematic review and meta-analysis of climate-health relationships

## Data Processing Notes
- Large files (>100MB) are stored using Git LFS
- CSV files contain cleaned and processed data ready for analysis
- Excel files may contain multiple sheets with different data views

## Research Applications

This collection supports research in:
- Climate change impact on respiratory health (COPD focus)
- Air quality and temperature effects on healthcare utilization
- Healthcare facility sustainability and carbon footprint analysis
- Environmental justice and health disparities
- Climate adaptation strategies for healthcare systems

## File Formats
- **CSV**: Structured data for analysis
- **XLSX**: Excel workbooks with multiple data views
- **IPYNB**: Jupyter notebooks for data processing and analysis
- **DOCX**: Documentation and methodology descriptions

## Data Quality and Methodology
- Apollo Hospitals data is synthetically generated following clinical data patterns
- Milliman data includes validated air quality and temperature measurements
- System data represents aggregated research findings from multiple sources
- Practice Greenhealth data is self-reported by healthcare facilities