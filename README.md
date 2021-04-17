# Surfs Up

## Overview of the analysis
For Semi-anaual periods Ary would like to know if the temperature is consistent. Not only the atmospheric temperture but ideal weather conditions for ice cream and surffing, which if prove favorable, he will start with his new franchise of surf and ice cream shop. We will use temperture trends for the months June and December over a period of eight years of data gathered and store in the data file, hawaii.sqlite.

## Results
The major task in this analysis was to extract the momths involved in the analysis. Tools provided by Sqlalchmey extract, was sufficent to query for the required information.The describe function (.describe()) gives statistical details such as percentile, mean and standard deviation etc. of a data frame or a series of numeric values. Tables 1 and 2 shows the result using the describe function.
### Table 1
![Table 1](https://user-images.githubusercontent.com/78861458/115090100-f3337c80-9ee1-11eb-9d4c-1a70907c4652.png) 
### Table 2
![Table 2](https://user-images.githubusercontent.com/78861458/115090131-07777980-9ee2-11eb-9935-a55c15cb1891.png)

There are three major points that are determine from the two deliverables:
1. Tempertures at the beginning of the summer, June, and for the month of Deecember are same, each quartile has the same range. However, December has a reduction in temperture, with each quartile of three (3) degrees fahrenhite.
2. The maximun tempertures for each periods are the same with mininum in the month of December far less than that in June.
3. There is a difference of aproximatly three(3) degrees fahrenheit for the average tempreture between two(2) months.

 Standard deviation for June is 3.257417 and for December 3.745920, the value for each period only show a slight difference which gives the indication that the average temp maybe  consistent throughout the year. The inspect function in sqlachemy can provide a look into the two tables, Measurement and Station, for more information to query that can provide a better picture in our analysis. Rainfall could be a factor in our business plan, since beach attendance will be reduced during this time. The column name "prcp" that gives data for perciptation can provide the average rainfall for both month. Stations location has an important part in this equation, the station table gives the location and elevation for each of the different station "id".





