# Tableau Homework - Citi Bike Analytics

https://public.tableau.com/profile/michael2102#!/vizhome/citi_bike_station_15802699517440/StartStations?publish=yes

### Before You Begin

* This assignment will be saved to your tableau public account rather than github. 

* If you haven't already, be sure to create a tableau public account [here](https://public.tableau.com/s/).

* The free tier of tableau only lets you save to their public server. This means that each time you save your file it will be uploaded to your tableau public profile. 

* You are able to load and continue working on the same workbook.

* When you are finished with your assignment, you will turn in the URL to your tableau public workbook along with any additional files used for your analysis. 

## Background

![Citi-Bikes](Images/citi-bike-station-bikes.jpg)

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

## Task

**Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.** 

**Design 2-5 visualizations for each discovered phenomena (4-10 total). You may work with a timespan of your choosing. Optionally, you may merge multiple datasets from different periods.** 

**The following are some questions you may wish to tackle. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!**

* How many trips have been recorded total during the chosen period?

5,029,334 rides combined for July 2016, 2017 and 2018

* By what percentage has total ridership grown?

Ridership has grown for the month of July year over year from 2016 to 2017 by 7.07% and from 2017 to 2018 by 3.54% respectively

* How has the proportion of short-term customers and annual subscribers changed?

While short-term customer ridership has barely grown (July 2016 to 2017 by 1.19% and July 2017 to 2018 by 0.46%), annual subscribers have grown by 5.88% and 3.07% since 2016 to 2018 with a total growth of almost 9% over the chosen period (month of July)

* What are the peak hours in which bikes are used?

Unsurprisingly, the most popular hours were at 8:00am and 5:00pm/6:00pm which correlate to rush hours for the morning and evening commuters

* Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)

Pershing Square North
West St & Chambers St
12th Ave & W. 40th St
E 17th St & Broadway
W 21st St & 6th Ave
Broadway & E 22nd St
W 20th St & 11th Ave
Central Park S & 6th Ave
Broadway & E 14th St
South End Ave & Liberty St.
Based on the data of bike stations in the city for starting a journey the above locations are top 10 because they are near major transportation hubs (MTA stations), and also near bike routes (i.e. Central Park, Westside Highway) which are popular amongst riders

* Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)

Pershing Square North
West St & Chambers St
12th Ave & W. 40th St
E 17th St & Broadway
W 21st St & 6th Ave
Broadway & E 22nd St
W 20th St & 11th Ave
Carmine St & 6th Ave
South End Ave & Liberty St
Broadway & E 14th St
The top 10 end vs. start stations are the same with the exception of Carmine St & 6th Ave and Central Park S & 6th Ave. However Carmine St & 6th Ave is also near a park (Washington Square Park)

* Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)

The bottom 10 stations for ending a journey are also similar to the bottom 10 stations in the city for starting a journey

The bottom 10 stations for starting a journey are either at NYC bus stations or in Brooklyn, and outside of Manhattan, which has the largest concentration of bike stations

* Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)

* Today, what is the gender breakdown of active participants (Male v. Female)?

As of July 2018 there are:
64.93% Male
24.05% Female
11.02% Unknown

* How effective has gender outreach been in increasing female ridership over the timespan?

Female ridership has increased year over year but male ridership still far outpaces all genders

* How does the average trip duration change by age?

In 2016 the average ages for trip durations was relatively steady, meaning that across all ages trip durations were quite similar
In 2017 there are stark noticable differences in that 32, 21 and 24 year olds comprised the top 3 ages for longest trip durations
In 2018 the top 3 ages shift to 50, 18 and 42 year olds with the longest trip durations

* Which bikes (by ID) are most likely due for repair or inspection in the timespan?

There are 12 bikes that are have been ridden over 4 million seconds (over 1,000 hours) that are at the highest risk of repair or inspection, and 4 bikes that have surpassed over 6 million seconds (1,666 hours)

**Next, as a chronic over-achiever:**

* Use your visualizations (does not have to be all of them) to design a dashboard for each phenomena.
* The dashboards should be accompanied with an analysis explaining why the phenomena may be occuring. 

**City officials would also like to see one of the following visualizations:**

* **Basic:** A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.

* **Advanced:** A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

* The map you choose should also be accompanied by a write-up unveiling any trends that were noticed during your analysis.

**Finally, create your final presentation**

* Create a Tableau story that brings together the visualizations, requested maps, and dashboards.
* This is what will be presented to the officials, so be sure to make it professional, logical, and visually appealing. 

## Considerations

Remember, the people reading your analysis will **NOT** be data analysts. Your audience will be city officials, public administrators, and heads of New York City departments. Your data and analysis needs to be presented in a way that is focused, concise, easy-to-understand, and visually compelling. Your visualizations should be colorful enough to be included in press releases, and your analysis should be thoughtful enough for dictating programmatic changes. 

## Submission 

Your final submission should include:

* A link to your Tableau Public workbook that includes: 
  * 4-10 Total "Phenomenon" Visualizations 
  * 2 Dashboards
  * 1 City Official Map
  * 1 Story 
* A text or markdown file with your analysis on the phenomenons you uncovered from the data.

## Assessment

Your final product will be assessed on the following metrics:

* Analytic Rigor

* Readability

* Visual Attraction


## Hints

* You may need to get creative in how you combine each of the CSV files. Don't just assume Tableau is the right tool for the job. At this point, you have a wealth of technical skills and research abilities. Dig for an approach that works and just go with it.

* Don't just assume the CSV format hasn't changed since 2013. Subtle changes to the formats in any of your columns can blockade your analysis. Ensure your data is consistent and clean throughout your analysis. (Hint: Start and End Time change at some point in the history logs).

* Consider building your visualizations with small extracts of the data (i.e. single files) before attempting to import the whole thing. What you will find is that importing all 20+ million records of data will create performance issues quickly. Welcome to "Big Data."

* While utilizing all of the data may seem like a nice power play, consider the time-course in making your analysis. Is data from 2013 the most relevant for making bike replacement decisions today? Probably not. Don't let overwhelming data fool you. Ground your analysis in common sense.

* Remember, data alone doesn't "answer" anything. You will need to accompany your data visualizations with clear and directed answers and analysis.

* As is often the case, your clients are asking for a LOT of answers. Be considerate about their need-to-know and the importance of not "cramming in everything". Of course, answer each question, but do so in a way that is organized and presentable.

* Since this is a project for the city, spend the appropriate time thinking through decisions on color schemes, fonts, and visual story-telling. The Citi Bike program has a clear visual footprint. As a suggestion, look for ways to have your data visualizations match their aesthetic tones.

* Pay attention to labels. What exactly is "time duration"? What's the value of "age of birth"? You will almost certainly need calculated fields to get what you need.

* Keep a close eye for obvious outliers or false data. Not everyone who signs up for the program is answering honestly.

* In answering the question of "why" a phenomenon is occurring, consider adding other pieces of information on socioeconomic or other geographic data. Tableau has a map "layer" feature that you may find handy.

* Don't be afraid to manipulate your data and play with settings in Tableau. Tableau is meant to be explored. We haven't covered all that you need -- so you will need to keep an eye out for new tricks.

* Treat this as a serious endeavor! This is an opportunity to show future employers that you have what it takes to be a top-notch analyst. 

* Good luck!

### Copyright

Data Boot Camp (C) 2019. All Rights Reserved.
