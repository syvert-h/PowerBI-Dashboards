# Stolen Vehicles NZ Dashboard

PowerBI dashboard looking at stolen vehicles in NZ in the past 6 months (June 2021 - January 2022).

### Motivation:
Recently, it feels like there has been a spike in burglary, especially among the youth. A type of burglary making headlines in the news today is ram raids. These types of burglaries require vehicles, so it had me thinking: **"What kind of cars are susceptible to thieves?"**. 

### Installation:
To access the dashboard, download the zip file. It contains the PowerBI file along with the dataset(s) used.

### More Background:
The dataset of stolen vehicles was obtained here: https://www.police.govt.nz/can-you-help-us/stolen-vehicles. This contains information on stolen vehicles in the past 6 months.

This dataset alone did not contain enough information about the vehicles. So, I obtained a large dataset of *all registered vehicles in NZ* from: https://opendata-nzta.opendata.arcgis.com/datasets/NZTA::motor-vehicle-register-api/explore . This contained information more detailed information about the vehicle such as engine size, fuel type, number of seats, and more.

These two datasets were merged to produce a detailed description of *almost* every stolen vehicle in the past 6 months.

### Quick Insights:
- There have been 5280 reported vehicle thefts in NZ from July 25th to January 22nd.
- January 2023 saw an 11.32% increase in theft compared to December 2022. There have been 1072 thefts alone in January 2023 (53%).
    - Note: this may need further investigation - since the dataset may be updated if older vehicles are recovered.
- Cars built in 2010 or older account for 71.25% of thefts.
- Stationwagon, Saloon, and Trailer make up the top 3 most stolen vehicle types.
- Auckland has seen at least 872 thefts in the past 6 months.

**Note: Stolen vehicles which have been recovered are removed from the database; Hence, comparing month to month is not of much use.**