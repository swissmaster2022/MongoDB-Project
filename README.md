# MongoDB-Project Analyzing U
MongoDB Project Analyzing US Airline Flight Delay

The Airlines JSON File from CORGIS Dataset Project
(https://think.cs.vt.edu/corgis/datasets/json/airlines/airlines.json) was my dataset of choice. This
dataset contains monthly data on US flights delays, airports, airlines, years, months and detailed
information on the cause of delays. There are approximately 29 major US airports data and 4408
JSON records.
My goal is also to derive some additional data using City or State and currently this information
is not included in the first dataset. My second separate dataset of choice that includes all Airport
2
codes in the world including geographical information such as name, airport code and name, city,
state and country is found here https://think.cs.vt.edu/corgis/datasets/json/airlines/airlines.json.
Analysis will be to try to answer the following questions with the given data. It is essential to
mention that this is a very small extract of the data available. Although there are over 19,000
airports in the US, only 37 Airports are class B airports. This dataset consists of 29 of the Class
B (https://en.wikipedia.org/wiki/List_of_Class_B_airports_in_the_United_States) airports.
The goal is to extract only 2015 data for all 29 airports to address the following questions. The
Airline Delay dataset will be joined with the World airport codes to obtain the city and state
names.
1. Top 5 Airports with the largest number of delays
2. Top 5 States with the largest number of delays
3. The Top 3 Months in 2015 with the highest number of delays
4. The Airlines with highest number of Delays
