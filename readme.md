#AQI Project 3
This was a challenging project that was supposed to be done with a group to spread the work needed to create a useful tool. Sadly, this did not happen. The intent was to determine if areas having greater population were more prone to the air particles linked to respiratory illnesses. 

## Data
Data was obtained from several locations:
* CDC: [CDC Link!](https://data.cdc.gov/NCHS/Monthly-Provisional-Counts-of-Deaths-by-Select-Cau/9dzk-mvmi/data) To gather respiratory deaths by state and year.
* OpenWeather: [OpenWeather Link!](https://openweathermap.org/api/air-pollution) To gather Air Quality measurements and locations.
* EPA: [EPA Site for Facts!](https://www.epa.gov/clean-air-act-overview/air-pollution-current-and-future-challenges) To gather information on respiratory diseases.
* Census: [Census site for population data!](https://www.census.gov/data.html) To gather population data for the 2020-2022 years

## Process
<ul>
   <li>Obtained historical data on respiratory deaths in the United States for the years 2020-2022.</li>
   <li>Obtained historical data for populations by city </li>
   <l1>Obtained historical data for air quality from sensor readings across the United States</li>
   <li>Stored all historical data in a PostgreSQL Database. </li>
<li>All cleaning, joining, and aggregation occurred within the database. (See the DDL and ERD folder for details).</li>

   <li><ul>Questions to determine what types of visualizations should be displayed:</li>
   <li>    How many people die each year in each state from a respiratory problem? </li>
   <li>    How many times a year does a state suffer from poor air quality?</li>
   <li>   Where are the air quality stations located in the United States? and What are their results?</li>
   <li>    What was the highest AQI Index category and death count for each state in any given year? </li>
</ul>
<li>Queried the database to attempt to answer these questions.</li>
<li>Extracted the data and loaded it into JavaScript files in CSV format. (Issues occurred when JSON conversion was attempted-corrupted dictionaries).</li>
<li>Created Interactive Plotly and Leaflet visualizations for end users to explore the data.</li>

## Conclusion
There was not enough time to correlate the death counts with the locations having increased counts of poor air quality- no conclusions were made. If we had a better random group, this could have been a better project- instead, I was left with very negative feelings about javascript and group projects in general. 
<ul>My portion:
<li>Collected data</li>
<li>loaded into database</li>
<li>queries to join and transform data</li>
<li>javascript to create all interactive plots (except leaflet map--one person of the 4 on our group assisted here)</li>
<li>flask app</li>
<li>all html/css work to implement navigateability and style </li>
</ul>

## Finding the positive: I am capable of creating a working application using javascript, flask, html/css with nearly zero help in under two weeks. 