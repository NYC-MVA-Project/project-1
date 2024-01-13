# NYC MVA Project
# By Robert Rose, Cataldo Cocuzza, Adrian Dayrit

Overview:
•	Our proposal was to find different trends and patterns for motor vehicle accidents in New York City
o	Top causes
o	Accident hot spots
o	Borough data
o	Car vehicle type
o	Time of day
o	Pandemic trends
o	Safest and least safe intersections
Two hypotheses going into the project:
•	The pandemic impacted traffic in an obvious way, and that traffic accidents increased afterwards
•	Driver inattention would dominate the causes

Intro to Data
	Our sample size used was 1,000,000 rows of data starting from 2017 to 2023
	This data included:
	  Crash date/time
	  Street name/borough
  	Number of people injured/killed
  	Contributing factor
	Type of vehicles
Obtaining and Scrubbing of Data
Used the City of New York API to obtain data and ultimately save it to .CSV format to read.
This also involved having to:
o	Fix date field formatting
o	Remove NaN’s or unspecified date in pertinent columns
o	Remove the “Unnamed: 0” column that was coming from the .CSV file
o	Scrubbing this data dropped the row count down to 441,328 rows
Breakdown of Data and 
o	63.9% of accidents happen in the day/afternoon as opposed to night/early morning
o	Top 10 accidents that happen during the day include:
	Driver inattention/distraction
	Backing unsafely
	Driver inexperience  
	Alcohol involvement
	Brakes defective
	Accelerator defective
	Cell phone usage
o	Top 10 accidents that happen at night:
	Driver inattention/distraction
	Backing unsafely
	Alcohol involvement
	Driver inexperience 
	Aggressive driving
	Animals action
	Cell phone usage
	Mechanical issues
o	Top vehicles involved in accidents are:
	Sedans
	SUVs/station wagons
	Taxis
o	Deaths by vehicle types are:
	Sedans
	SUVs/station wagons
	Motorcycles
o	NYC boroughs with the most accidents
	Brooklyn
	Queens
	Manhattan
	Bronx
	Staten Island
o	Trends of Accidents from 2017 to 2023
	Accidents held steady ranging from ~8k to ~10k accidents per year from 2017 to 2020.
	Once the pandemic hit in 2020, there were ~2k accidents during that year
	Once things started to open back up from 2021 to 2023, accidents remained steady from ~3.5k to ~4k accidents per year.
o	The top months with most accidents
	Trends showed that during warmer months, more accidents occurred
	Colder months yielded less accidents overall
o	Days with the most accidents
	Trends showed that most accidents happened on Fridays and Thursday
	Less accidents happened over the weekend
o	Deaths by Year
	Surprisingly the most fatalities happened during 2020
	This was attributed to people more reckless on the road due to there being less people overall travelling
o	Deaths by Month
	Concurrently with accidents, fatalities occurred more often during warmer months than colder ones
o	Conclusions
•	We partially confirmed our hypothesis.
•	Accidents saw a precipitous drop during the pandemic, however, our data seems to not extend far beyond 2022. While we have some data, the volume is too low to confirm anything.
•	Our data did confirm that driver distraction is far ahead of the causes of accidents, both day and night. We also noticed a large increase in alcohol related accidents overnight.


•	We discovered some other interesting facts.
•	The most/least dangerous intersections in the city.
•	Couldn’t determine why they are dangerous based on the data.
•	The most and least dangerous months for driving in the city. We assumed maybe winter because of driving conditions, but it appears the warmer weather might bring out more drivers.
•	The most dangerous day of the week for driving is Friday.
•	The most dangerous borough for driving is Brooklyn, they are the most populous borough and have the second highest population density.
	
