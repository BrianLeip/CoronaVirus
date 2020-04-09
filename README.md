# Covid-19 (Coronavirus) Analytics and Forecasting
***
*WORK IN PROGRESS*
***

## Files:
- **[Covid-19 (Coronavirus) Analytics and Forecasting (Jupyter Notebook)](https://github.com/BrianLeip/CoronaVirus/blob/master/Covid19_Analytics.ipynb)**
- [Extract, Transform, Load (ETL) Data preparation notebook for Covid-19 datasets](https://github.com/BrianLeip/CoronaVirus/blob/master/Covid19_Data_ETL.ipynb)

## Data Sources:

- **Primary Data Source:** Johns Hopkins CSSE Data Repository - https://github.com/CSSEGISandData/COVID-19  
    - Live data:
        - Countries (cases, deaths, recoveries, active)
        - US States (cases, deaths)
        - US County (cases, deaths)
    - Historic data:
        - Countries (cases, deaths, recoveries, active)
        - US States (cases, deaths)
        - US Counties (cases, deaths)
- **US State Testing and Hospitalizations:** Covid Tracking Project - https://covidtracking.com/data/  
    - Live data:
        - US State testing and hopspitalization, ICU stats **PENDING**
    - Historic data:
        - US State testing and hopspitalization, ICU stats **PENDING**
- **US County - Alternative:** NY Times - https://github.com/nytimes/covid-19-data/
    - Historic data:
        - US States (cases, deaths) **PENDING**
        - US Counties (cases, deaths) **PENDING**

## Methodology:
- Data is first gathered from various sources and then transformed into formats more conducive to EDA, analytics, and data viz with Python and various libraries like Pandas and Matplotlib
- All original data remains unchanged, only rearranged in a more usable format or summarized (e.g. Confirmed Cases subtotal by Country OR Deaths subtotal by US State)
- Reformatted files are exported daily at end of day to the `Datasets` folder 
- Data is then loaded into the Covid19_Analytics notebook for EDA, analytics, and forecasting
- See the [Covid19_Data_ETL file](https://github.com/BrianLeip/CoronaVirus/blob/master/Covid19_Data_ETL.ipynb) for the full Extract, Transform, Load process and logic

---
In addition to the Coronavirus Analytics Jupyter Notebook, I also did some simple forecasting in Excel on 3/15/2020 to predict the number of confirmed cases and estimated date when the US would go on full lockdown.  

**[US Confirmed Cases Forecasting from 2020-03-15 (Excel)](https://github.com/BrianLeip/CoronaVirus/blob/master/Covid19%20US%20Cases%20Tracking%20(Excel).xlsx)**


 