# ML assignement1b CSOC ML
Here is the first assignment of CSOC ML on the topics of Matplolib and pandas.

## Instructions to submit

Login into your GitHub account and fork this repo by clicking on the Fork button on the top right. You now need to clone the forked repository, complete the assignment, stage and commit the changes, and finally push the changes online. [This](https://try.github.io) interactive tutorial will help you cover the basics of Git.

Follow these commands to push your assignment after completion.
Using cd command go to your assigment folder where you clone it.Now type these commands.
  
>> git add -A  
>> git commit -m "Assignment_1b completed"  
>> git push origin master
<br> Open your repo on github and click the green button to create PULL REQUEST

If you are uncomfortable with command line, you can use Git GUI tool GitKraken. Install it from [here](https://www.gitkraken.com/download). After installing,
1. Login into GitKraken with GitHub
2. Choose Clone Repo (File -> Clone Repo)
3. Open the Repo
4. Complete the assignment.
5. Stage all changes (button on the right.)
6. Fill in the commit message and press commit.
7. Push the repo (button is on the top)

Finally fill the [google form](https://forms.gle/jyseWHBKwxhv5D3BA)


## Assignment_1_b- Pandas & Matplotlib


The 2nd part of this assignment helps you get familiar with Pandas functionalities and various Matplotlib operations you can do to generate various kinds of plots.

### Files Given_1

 kaggle_internet.csv:->This dataset contains data for counties with population over 65000, compiled from the 2016 ACS 1-year estimate. ACS 1-year estimates only summarize data for large geographic areas over 65000 population. The 2013-2017 ACS 5-year estimate is expected to be published at the end of 2018, which has data of all geographic areas down to block group level. Before that we will use the latest 2016 1-year estimate. It provides sufficient data for us to gain insight into internet use.

                     This dataset is created with totalcensus package for R programming. Here are the list of columns:

                     *county: name of the county
                     *state: abbreviation of the state where the county is in
                     *CEOID: geographic identifier for the county
                     *lon: longitude of a point inside the county
                     *lat: latitude of the point
                     *P_total: total population
                     *P_white: population of white, single race
                     *P_black: population of black, single race
                     *P_asian: population of asian, single race
                     *P_native: population of native Indians and Alaska natives, single race
                     *P_Hawaiian: population of Hawaiian and Pacific Islanders, single race
                     *P_other: population of other people, single race
                     *P_below_middle_school: population with education at or below 8th grade
                     *P_some_high_school: population having some years in high school but without a diploma
                     *P_high_school_equivalent: population with high school diploma or equivalent
                     *P_some_college: Population having associate degree or some years in college without bachelor degree
                     *P_bachelor_and_above: population with bachelor, master, professional, or doctor degrees
                     *P_below_poverty: population living below poverty line
                     *median_age: median age of population
                     *gini_index: gini index
                     *median_household_income: median household income
                     *median_rent_per_income: median percent of income spent on rent
                     *percent_no_internet: percent of household without internet connection
### Files Given_2
day.csv:->  It is part of a Bike Sharing Dataset. This dataset relates the bike sharing counts with various factors like temperature, weather and season. 
                                    
                        The fields present in day.csv are:		
			* instant: record index
			* dteday : date
			* season : season (1:springer, 2:summer, 3:fall, 4:winter)
			* yr : year (0: 2011, 1:2012)
			* mnth : month ( 1 to 12)
			* hr : hour (0 to 23)
			* holiday : weather day is holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
			* weekday : day of the week
			* workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
			+ weathersit : 
					* 1: Clear, Few clouds, Partly cloudy, Partly cloudy
					* 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
					* 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
					* 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
			* temp : Normalized temperature in Celsius. The values are divided to 41 (max)
			* atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max)
			* hum: Normalized humidity. The values are divided to 100 (max)
			* windspeed: Normalized wind speed. The values are divided to 67 (max)
			* casual: count of casual users
			* registered: count of registered users
			* cnt: count of total rental bikes including both casual and registered
Assignment_1_b.ipynb - A Python notebook which needs to be filled by you at appropriate palces to complete the assignment. Read the comments and text in order to understand what is required to be done at each step. 


This part of the assignment require more time then the previous part. It is a introduction to different types of plots and subplots.On successfully filling a plotting function completely, the corresponding plot will get generated.
	




