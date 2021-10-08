#Tableau Homework - Citi Bike Analytics


Background

This analysis attempts to shed some light on the Citi Bike usage in NYC and NJ. Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the Citi Bike Data webpage.
However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. 
The date for this is from the website.  
In this analysis I only used data from 2019 and 2020.  I chose to exclude 2021 since the full year is not caputured, however, it must be noted that two years is a short time frame, and due to the COVID pandemic, 2020 data may be skewed.

The first step was to clean and transform that data. I chose to use Pandas/Jupyter Lab to do this.  I first read in all csv's for the years in question then combined them into one dataframe.  I then changed some data types, for example I changed 0, 1 and 2 into unknown, male and female for ease of readability. I also used the date of birth year provided to calculate age as of today.  Further, column names were renamed, again for readability.

Once this was complete I read out a final, single csv to use in Tableau.

Using this data several things became clear immediately.  

Usage changes with the seasons as expected, and Spring of 2020 was dramatically lower than Spring of 2019, again to be expected with the total shutdown of March 2020

Riders identified as male far outpace riders who are unknown or female.
![alt text](https://github.com/MWilliamsDP/TableauHomework/blob/main/Images/One%20Slide%20of%20Story.PNG)

The average age of riders, regardless of gender is between 35 and 52.


New Jersey actually has almost all of the stations where rides initiate.
![alt text](https://github.com/MWilliamsDP/TableauHomework/blob/main/Images/Maps%20wtih%20Zip%20Code%20Overlay.PNG)

Included in the files is a powerpoint that show the Tableau story in the event that the workbook cannot be opened since I saved it on my desktop account instead of the public account.


