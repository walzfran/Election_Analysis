# Election_Analysis

Module Three Challenge

# Election Audit in Python with Summary

## Overview of Election Audit

### The pourpose of this module was to create a code that can analyze the data from an election in Colorado. Tom and Seth were also looking for a code that could be applied to other data sets from elections. This analysis looks at the election results for 3 different counties in Colorado  - Denver, Arapahoe, and Jefferson. With the data set that we were given we ran code to see the total votes for all 3 counties, then the breakdown of how many votes as a percentage per county and then the winner of the election with the total votes and percentage breakdown. Below is an image that depicts the election results analysis that we performed in python. 

![Election_Results](https://github.com/walzfran/Election_Analysis/blob/main/Election_Results.png)

## Election Audit Results

### How many votes were cast in this congretional election?
* There were 369,711 votes total in the three counties : Jefferson, Denver, and Arapahoe
* This image depicts the python code results for the total number of votes

![Election_Total_Votes](https://github.com/walzfran/Election_Analysis/blob/main/Total_Votes.png)

  - Jefferson county had 38,855
    * This is 10.5% of the total votes
  - Denver county had 306,055 votes total in the three counties
    * This is 82.8% of the total votes
  - Arapahoe county had 11,606 votes total in the three counties
    * This is 6.7% of the total votes

#### This shows that Denver county had the highest amount of votes with the largest percentage of 82.8% of total votes in the congretional election
#### The image below depicts the python code results for the county breakdown with the largest turnout 

![County_Breakdown](https://github.com/walzfran/Election_Analysis/blob/main/County_Breakdown.png)

### Breakdown of Candidates
* There were three candidates running in this congretional election : Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane
  - Charles Casper Stockham
    * Number of Votes : 85,213
    * Percentage of Votes : 23%
  - Diana DeGette
    * Number of Votes : 272,892
    * Percentage of Votes : 73.8%
  - Raymon Anthony Doane 
    * Number of Votes : 11,606
    * Perentage of Votes : 3.1%

#### This shows that Diana DeGette was the winner of the election with the majority of votes as her percentage was 73.8% which is much higher than the other two candidates.
#### The image below depicts the python code results for the candidate results with both number of votes and percentage

![Candidate_Breakdown](https://github.com/walzfran/Election_Analysis/blob/main/Candidate_Breakdown.png)

Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

## Election Audit Summary
### When starting this code, we were informed that Tom and Seth would want this to be versatile code so they could use it for other elections. Depending on what kind of election they were having you can alter the script to fit what they are looking for. We have created script that counts the total number of votes, we then break down the total number of votes by county and assign a percentage of the the toal votes cast and have the largest turnout county populated and then the same thing for the candidates whcih then populates the winner of the election. 

### The first thing you would have to do to apply this to other elections is change the data source, you would need to pull from a different dictionay .csv which would be done at the beginning of the script, below is an image that shows where the data is being pulled from. If you are working on an election with candidates and counties then you would not have to alter any of the other script 

![Election_Data](https://github.com/walzfran/Election_Analysis/blob/main/Data_Election.png)

### If you were to be using this script to populate results for a specific issue that may be on the upcoming election ballot such as question that have a yes or no answer such as voting on millage or constitutional updates. In this instance you would need to alter the candidate information to millage information that would then yeild a percentage based on a yes or no answer vs. a candidates name. This would be a simple alteration that would then apply to really any sort of qustion that would be on an election ballot. 
