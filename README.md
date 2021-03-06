# Is there any relation between cancer death rate and GDP for all the countries around the world?

## Summary
We were interested in cancer mortality rate among different nations. Cancer is among the leading causes of death worldwide.In 2012,there were 14.1 millionn new cases and 8.2 million cancer-related deaths worldwide. 57% of new cancer cases in 2012 occured in less developed regions of the world that include Central America and parts of Africa and Asia; 65% of cancer deaths alsooccured in these regions.The number of new cancer cases per year is expected to rise to 23.6 million in 2030. 

The Gross Domestic Product measures the value of economic activity within a country.
Strictly defined,GDP is the sum of the market values, oor prices, of all final goods and services produced in an economy during a period of time.

In this project we tried to make a Dataset to see whether there is a correlation between cancer death rates and the GDP.I n less developed countries or regions rather than the number of deaths per year was very huge which mage us come with the following questions:

  - Is there any relation between cancer death rate and the GDP for all the countries around the world?
  - Which type of cancer is more common in a certain country?
  - How has the GDP rate been changing over the past 16 years from the year 2000 to 2016 per country?
  
## Extraction
 We exctracted our data from the following sources:
 
   - Gross Domestic Product for the whole world from 1960:
   - https://data.worldbank.org/org/indicator/ny.gdp.mktp.cd?view=map
   
## Transformation
We transformed our data from CSV files to Pandas DataFrames using jupyter notebook and did data claeaning of extracted data.

## Loading Data
We exported the pandas DataFrame in different formats for future use.
   
   - Saved data as a CSV file 
   - Saved data as a JSON file
   - Saved data as Postgres table in ETL_Project dataset.We can have other tables in Postgres like Age, Country and Cause to normalize the data if needed.

Prepared by: **Joyce Muthondu and Behnam Firoozfard**    
