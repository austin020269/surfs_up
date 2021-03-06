# surfs_up
UT Bootcamp Module 9 

## Project Overview
W. Avy is concerned about the amount of rain that the island of Oahu receives in order of possibly open up a surf and ice cream shop.  We were given precipitation and weather stations data at the beginning of the analysis.  In end he was more concerned with specific trends in the temperature data for the months of June and December in order to determine if a surf and ice cream shop business is sustainable year-round.


## Resources
Data Sources provided to analyze and minipulate included:
- hawaii.sqlite data file

Software utilized for this study included: 
- Python 3.7.6 
- Conda 4.9.2 
- Jupyter Notebook 6.1.4
- Personal GitHub account

## Analysis and Workflow
After importing depenedencies and our Python toolkit, we reflected our data into a new model, prepared the tables and saved the reference tables as measurement and station.  We then performed the following workflow for the months of June and December:

1. Write a query that filters the Measurement table to retrieve the temperatures
2. Convert the temperatures to a list
3. Create a dataframe from the list of temperatures
4. Calculate and print out the summary statistic

## Results

Deliverable 1 - June Weather Statistics

![alt text](https://github.com/austin020269/surfs_up/blob/main/June_statistics.PNG)

- Total 1700 stations 
- Average temperature was approximately 75 degrees 
- High and low temperatures were 85 and 46 degrees Farenheit, respectively.

Deliverable 2 - December Weather Statistics

![alt text](https://github.com/austin020269/surfs_up/blob/main/December_statistics.PNG)

- Total of 1517 stations 
- Average temperature was approximately 71 degrees 
- High and low temperatures were 83 and 56 degrees Farenheit, respectively.

## Summary
Based on June and December temperature data, Oahu looks like a great place to open a surf and ice cream shop showing that it has a warm to moderate climate year round.  Other queries I would use in this analysis would be precipitation and number cloudy days vs sunny days.  People tend to be outdoors surfing and eating ice cream when the sun is out.
