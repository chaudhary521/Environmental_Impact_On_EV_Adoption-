# Environmental Impact on Electric Vehicle Adoption in Washington State

A data-driven analysis exploring the relationship between air quality (PM2.5), EV registrations, and charging station availability across Washington State counties.

## Author
Vishal Chaudhary

## Overview
This project analyzes three key datasets to understand EV adoption trends:
- **Washington AQI Data** – PM2.5 readings from the EPA API
- **Alternative Fuel Stations Data** – EV charging station locations from the U.S. Department of Energy
- **EV Vehicle Registrations Data** – County-level EV registrations from data.gov

## Tech Stack
- **Python** (Pandas, Matplotlib)
- **MongoDB** – Raw data storage
- **PostgreSQL** – Relational data management

## Key Findings
- King County leads in EV registrations (~200,000) and has the highest PM2.5 levels
- Charging station count does not directly predict EV registrations (correlation: 0.25)
- Passenger vehicles dominate EV registrations across all counties
- Air quality is weakest in winter months (AQI peaks in November–December)

## Data Sources
- EPA Air Quality System: https://aqs.epa.gov/aqsweb/documents/data_api.html
- U.S. DOE Alternative Fuels Data Center: https://afdc.energy.gov/stations/
- Data.gov EV Registrations: https://catalog.data.gov/dataset/vehicle-registrations-by-class-and-county
