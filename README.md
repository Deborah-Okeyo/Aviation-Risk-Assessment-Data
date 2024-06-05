# Aviation-Risk-Assessment-Data
# **ON THIN AIR: UNDERSTANDING AVIATION RISKS THROUGH DATA ANALYSIS**
 In pursuit of expanding into new industries with the aim of diversifying the company's portfolio, our company sets on venturing into the aviation industry. This therefore creates a need for understanding and mitigating potential risks. The goal is to provide insights from data analysis techniques so as to empower our company to make informed decisions before venturing into aviation. This analysis will help inform the company's strategy for entering the new market.

 ## Objectives

 1. Conduct an analysis of aviation accident data from the National Transportation Safety Board.
2. Identify trends and patterns on the data in order to assess risk factors associated with different aircrafts.
3. Generate recommendations that will aid in decision-making on which aircraft to purchase for both commercial and private enterprises

## Data Understanding

The data for this analysis is from the National Transportation Safety Boardthatincludes aviation accident data from 1962-2023 about civil aviation 
accidents and selected incidents in the United States and international waters. It is an independent federal agency charged by congress with investigating every civil aviation accident in the US and significant events in other modes of transport.
the data is contained in two seperate csv files:

1.[AviationData.csv](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses?select=AviationData.csv): each record represents an event with 31 attributes:

'Event.Id', 'Investigation.Type', 'Accident.Number', 'Event.Date', 'Location', 'Country', 'Latitude', 'Longitude', 'Airport.Code', 'Airport.Name', 'Injury.Severity', 'Aircraft.damage', 'Aircraft.Category', 'Registration.Number', 'Make', 'Model', 'Amateur.Built', 'Number.of.Engines', 'Engine.Type', 'FAR.Description','Schedule', 'Purpose.of.flight', 'Air.carrier', 'Total.Fatal.Injuries','Total.Serious.Injuries', 'Total.Minor.Injuriries','Total.Uninjured','Weather.Condition', 'Broad.phase.of.flight', 'Report.Status' and'Publication.Date'

2.[USState_Codes.csv](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses?select=USState_Codes.csv); contains:

'Name of the state' and 'The state abbreviation'

## Data Analysis
![output](https://github.com/Deborah-Okeyo/Aviation-Risk-Assessment-Data/assets/170344939/a3423853-c8ad-4eb5-a8c3-b7e6fd7da169)

![output](https://github.com/Deborah-Okeyo/Aviation-Risk-Assessment-Data/assets/170344939/fdcf69db-c79c-4130-b07e-43718161144b)

![output](https://github.com/Deborah-Okeyo/Aviation-Risk-Assessment-Data/assets/170344939/ed779c05-9dd2-4dca-a5ad-e01ca71cf27c)

![output](https://github.com/Deborah-Okeyo/Aviation-Risk-Assessment-Data/assets/170344939/b414ddc5-268e-42fe-8adb-2b04de645f44)

![output](https://github.com/Deborah-Okeyo/Aviation-Risk-Assessment-Data/assets/170344939/94746c30-4517-4705-ae15-b157c1c97b25)

![output](https://github.com/Deborah-Okeyo/Aviation-Risk-Assessment-Data/assets/170344939/ea95813a-6945-47e3-8027-28a18e3983c3)

## Summary

Based on the bar plots, the aircraft models least involved in accidents are GC-1-A, 737-3S3, MBB-BK117-B2, GLASSAIR GL25, and M-8 EAGLE. These models have a more evenly spread frequency distribution, suggesting they are less frequently involved in accidents.

The models most involved in accidents are 152, 172, 150, 172N, PA-28-140, and 150. Among these, the model 152 dominates the dataset in terms of frequency.

When purchasing an aircraft, it is advisable to consider models that are least involved in accidents. These models are less frequently associated with accidents, based on the data analyzed.

The histograms suggest that aircraft with 3 engines are more preferable. Makes to be considered include Gideon, Brault, Kircher, 1977 Colfer-chan, Leonard Walters, Maule Air Inc., Moltey Vans, Perlick, and ROYSE RALPH L.

There is a negative correlation observed between the total number of injuries and the model of the aircraft. This implies that as the aircraft models become newer, the total number of people injured tends to decrease.

The severity of injuries tends to increase as the level of aircraft damage increases. This relationship underscores the importance of maintaining aircraft in good condition to minimize the severity of injuries in case of accidents.

## Conclusion

When selecting an aircraft for purchase, it is recommended to choose models that have been least involved in accidents based on the historical data analysis. Additionally, ensuring the aircraft is in good condition and has a higher number of engines may contribute to better safety outcomes. Maintaining newer models and keeping the aircraft in good condition can help reduce the severity of injuries in the event of an accident. Finally, newer models are preferable as thet often incorporate the latest technologies and design improvements. They may also come withbetter training programs for pilotsas well as updated safety procedures.






