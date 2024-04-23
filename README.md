# life_expectancy_analysis
Here we have two different files
  1) Country Life Expectancy data with country, Year, lifeExp, and gdp(the continent column doesnt include all continents)
  2) Second Dataset CountryContinent Consists of Continents for the countries in the first dataset(countryLifeExpectancy.csv)
Step-1:
  We will merge both of these files and check for any uncleaned data columns.
Step-2:
  The continent column has spaces in the names
  So we will remove the spaces using .strip() method and rename the column from 'continent ' to 'continent'
Step-3:
  Now we will filter the data and save it in a sepereate variables based on our requirements.
Step-4:
  We will plot the graphs based on our ideas.
