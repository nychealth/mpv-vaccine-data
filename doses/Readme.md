
# doses/ 

This folder contains data on MPV vaccines that were administered by vaccinating facilities in NYC and reported to the CIR. 
This includes doses that were administered to NYC residents and non-NYC residents, such as individuals who work or study in NYC.

Second Dose data is available as of 10/27/2022
## Files 

### summary-doses.csv

This file contains information on the total number of vaccines delivered, and administered in NYC (UPDATED WEEKLY ON THURSDAYS). 

Indicators include:

|Variable Name |Definition |Timeframe|
|--------------|-----------|----------|
|group |Specific demographic group based on borough, race/ethnicity, age, and gender  | |
|admin_dose1 |Cumulative number of first doses administered of a two-dose MPV vaccine series (Dose 1 of 2) |Cumulative |
|admin_dose2 |Cumulative number of second doses administered of a two-dose MPV vaccine series (Dose 2 of 2) |Cumulative |
|admin_total |Cumulative number of MPV vaccine doses delivered or administered (Dose 1 of 2; Dose 2 of 2 |Cumulative |


### doses-by-day.csv   
This file contains information on the daily and cumulative numbers of MPV vaccine doses administered by vaccinating facilities in NYC.
These data represent doses and should not be used to calculate the number of individuals who are vaccinated. 

This file includes data since May 03, 2022 based on the date that the Health Department began its vaccination campaign against the MPV outbreak in NYC (i.e., date of the first administered vaccine). 

Indicators include: 

|Variable Name |Definition |Timeframe|
|--------------|-----------|----------|
|date |Date	|	|
|admin_dose1_daily |Daily number of first doses administered of a two-dose MPV vaccine series (Dose 1 of 2)|Daily, by date of vaccination |
|admin_dose1_cumulative |Cumulative number of first doses administered of a two-dose MPV vaccine series (Dose 1 of 2) |Cumulative |
|admin_dose2_daily |Daily number of second doses administered of a two dose MPV vaccine series (Dose 2 of 2) |Daily, by date of vaccination |
|admin_dose2_cumulative |Cumulative number of second doses administered of a two-dose MPV vaccine series (Dose 2 of 2) |Cumulative |
|admin_alldoses_daily |Daily number of all MPV vaccine doses administered (Sum of Dose 1 of 2; Dose 2 of 2) |Daily, by date of vaccination |
|admin_alldoses_7day_avg |7-day moving average of all MPV vaccine doses administered  (Sum of Dose 1 of 2; Dose 2 of 2) |Current day and previous 6 days |
|admin_alldoses_cumulative |Cumulative number of all MPV vaccine doses administered (Sum of Dose 1 of 2; Dose 2 of 2) |Cumulative |
|incomplete | Used for display purposes only|
