# Project2-Team3

ETL of Covid-19 data sets


Extract: 

  Data Sources

  1. Covid-19 in USA-Number of Novel Corona Virus 2019 cases in USA  from Kaggle.com
     3 csv files (primary)
   
     Reference Link: https://www.kaggle.com/sudalairajkumar/covid19-in-usa?select=us_counties_covid19_daily.csv
   
  2. State, County, CBSA, Country API Data from Covid Act Now (primary)
   
     Reference Link: https://apidocs.covidactnow.org/data-definitions/

  3. United States COVID-19 Cases and Deaths by State over Time from Data.CDC.gov and Splitgraph
     file can be exported as Json or downloaded as SQL_Query (Back up)
  
     Reference Link: https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36
                     https://www.splitgraph.com/cdc-gov/united-states-covid19-cases-and-deaths-by-state-9mfq-cb36
                  

Transform:

  1. Use Python Pandas to do Data cleaning, selecting, joining, and filtering (need to figure out use pandas to read json file)
  
  2. Python request library to pull data from API.

Load: 

   load the final result to Postgres pgAdmin4.
