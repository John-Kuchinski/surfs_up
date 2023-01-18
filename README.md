# Surfs_up

## Data

- hawaii.sqlite

## Resources/ software
  * Python    * SQLite   * SQLAlchemy   * Pandas  * Numpy
  * Jupyter   * Flask    * VS Code
 

## Overview

In this module we had some very simple questions, but in order to answer those questions and set up a system that can be reusable we had to take multiple steps. The overall purpose of this module was to help W. Avy in determining if he would like to invest in a "Surf and Shake" Shop located in Hawaii. We wanted to get the answers of the average, min, and max of both temperatures and rainfall over the last year to aid in the decisions making process. We performed analysis on the data over a year time span and these steps included getting or retrieving the data using json, formatting that information into readable dataframes, generating lists using query methods for both SQLite and SQLAlchemy, applying them to a local host as an http link for presentation. All items used are listed above and examples will be listed below. 

** Results
We selected the months of June and December to run tests of our queries on in order to get sample data should someone be looking at a specific month for travel/ vacation. These months seem to be great choices as June is in the summer for the USA and December is a great travel month for much of the country to escape the cold weather. The information gathered below should be a great representation of the data and can help us infer the weather at some given points through out the year.

First below is an example of given precipitation over the course of some time in order to help determine if it should be of any issue

![precipitation](https://user-images.githubusercontent.com/114188120/213273151-9a71edec-70a9-447a-8841-280682da3b70.png)


Here is an example of the data retrieved that has been jsonified prior to turning it into a readable Pandas data frame.

![december_info](https://user-images.githubusercontent.com/114188120/213271577-d96b4801-bfe4-458b-9e7e-1536449b65b4.png)

Here is one of the data frames created in order to list the June Temperatures.

![june_temps](https://user-images.githubusercontent.com/114188120/213271395-2494738c-8b8f-46aa-a8e6-d54ac0c9480b.png)

This is the December temperatures.

![dec_temps](https://user-images.githubusercontent.com/114188120/213271558-47b89a79-ec87-4458-8b45-51d3248a9daa.png)


Here are the corresponding descriptive statistics for the temperatures in the given months above.

![june_stats](https://user-images.githubusercontent.com/114188120/213271790-568e87d3-5eeb-4e22-a61b-1591d8c7e559.png)

![dec_stats](https://user-images.githubusercontent.com/114188120/213271825-b5d64d8e-5713-407e-9b28-d5d6663a1b93.png)

As you can see from the images above there are a few differences between June and December:

Both December and June have consistent temperatures, as the Standard Deviation is between 3 and 4 degrees for both months.
* The minimum temperature of December is 8 degrees lower than the minimum of June.
* The median and average temperatures of December are slightly lower than the median and average of June.
* The maximum temperature of December is only 2 degrees lower than the maximum of June.

## Summary

1. Precipitation should not be an obstacle, like most island climates there will be months out of the year that will have higher average precipitation than others, but good news, a high number of travelers that are coming to surf are coming to get wet!
2. 
3. Temperature likewise should be of little to no concern as from the peak of summer to the middle of winter there is typically less than a 10 degree shift in average temp! The data frames listed above show that the variation between multiple core statistics of the temperatures show a moderate range of change!
4. I believe that to prepare for some of these small inconveniences we can offer different apparel and food items to combat for any change in weather! Exapmles being wet suits and rain jackets for heavy precipitation months and even additional warm beverages such as hot chocolate and coffee can be offered for our patrons!
5. In addition I believe that some additional queries can be performed in order to gather even more concrete data such as additional months per season (May, June, July, and August) for the summer, and then (November, December, and January) for the winter months! I think this along with some additional data will allow us to allocate space in the shop for certain items and can even build in a rotation in the system to change out inventory. After doing these I believe it could increase over all sales and profitability (yes as an investor we know that is what you like to hear).

## Conclusion
With the data that has been gathered above, it should be more than helpful in aiding the decision to invest in the Surf and Shake shop. From my findings the only questions left are WHERE do we set up shop and WHEN do we get started!?
