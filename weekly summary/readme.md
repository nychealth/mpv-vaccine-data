# Weekly Summary/ 
This folder contains data on mpox vaccines that were administered by vaccinating facilities in NYC and reported to the CIR. This includes doses that were administered to NYC residents and non-NYC residents, such as individuals who work or study in NYC.

## Definitions:
- **Doses Administered:** The number of monkeypox vaccine doses that have been administered in NYC and reported to the CIR. This includes doses administered to NYC residents and non-NYC residents.
- **Dose Number:** Dose information is determined by the sequence of dates of vaccination event in the CIR. Data are broken out by the two-dose JYNNEOS vaccine series.
-- **Dose 1:** First dose of a two-dose vaccine series
-- **Dose 2:** Second dose of a two-dose vaccine series

## Demographic groups: 
A large proportion of the mpox vaccination data reported to the Citywide Immunization Registry (CIR) come from proprietary health care provider EHR systems that are not managed by the NYC Health Department. Data in the CIR are limited to what is available in EHR systems and to the fields required for submission. For example, information on race and ethnicity can be incomplete. 
Differences in health outcomes among demographic groups are due to long-term structural biases, not biological or personal traits. People who experience bias or stigma based on one or more aspect of their identity (race/ethnicity, gender identity, sexual orientation, class/income) are more likely to experience health inequities based on historical and ongoing systemic oppression. Structural biases — centuries of discriminatory policies and practices across institutions, including government agencies, and society — prevents historically disadvantaged communities from accessing vital resources (such as health care, housing and food) and opportunities (such as employment and education), and negatively affects overall health and well-being.
### Race and ethnicity
Race/ethnicity information is often missing in reportable disease surveillance as data are collected from self-reports to the vaccinating facility or to the CIR. 
The Health Department classifies race/ethnicity into the following mutually exclusive categories: Asian/Pacific-Islander, Black/African-American, Hispanic/Latino and White. The Hispanic/Latino category includes people of any race, and all other categories exclude those who identify as Hispanic/Latino.

## Files 
##### weekly-doses-raceeth.csv
##### weekly-doses-borough.csv 

These files contain information on the total number of vaccines administered in NYC by dose type and group. 
Indicators include: 
| Variable Name |	Definition	| Timeframe |
|----------|------------------------------|-------------|
| group	|Specific demographic group based on borough of residence, race/ethnicity and age | |
| admin_dose1	|Weekly number of first doses administered of a two-dose mpox vaccine series (Dose 1 of 2)	| Weekly; by date of vaccination|
| admin_dose2	| Weekly number of second doses administered of a two-dose mpox vaccine series (Dose 2 of 2)	|Weekly; by date of vaccination|
| admin_dose1_cumulative	| Cumulative number of first doses administered of a two-dose mpox vaccine series (Dose 1 of 2)	| Cumulative | 
|admin_dose2_cumulative |	Cumulative number of second doses administered of a two-dose mpox vaccine series (Dose 2 of 2)	| Cumulative |
|admin_total	| Weekly number of mpox vaccine doses administered (Dose 1 of 2; Dose 2 of 2)	| Weekly; by date of vaccination |
| admin_total_cumulative	| Cumulative number of mpox vaccine doses administered (Dose 1 of 2; Dose 2 of 2)	| Cumulative | 
