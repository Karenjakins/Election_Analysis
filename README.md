# Election Analysis

## Project Overview

Analysis for an election audit of the Colorado Board of Elections for a recent local congressional election, to determine the winning candidate and the largest voter turnout based on county. The analysis required the follwing data to be presented:

1. The total number of votes cast.
2. The list of all candidates in the election.
3. The total number of votes received per candidate.
4. The total number of votes per county. 
4. The percentage of votes for each candidate. 
5. The winner of the election.
6. The county with the largest voter turnout. 

## Election Audit Results 

- After conducting the analysis, a total of **369,711** votes were cast during this congressional election from the counties in the precinct, those being Denver, Jefferson, and Arapahoe. As can be referenced on the image below, the breakdown of the total votes per county lists Denver, the county with the largest number of votes, with an **82.8%** of the popular vote achieving a total of **306,055 votes**. The county of Jefferson received a **10.5%** of the popular vote with **38,855** votes while Arapahoe received **6.7%** of the popular vote with a total of **24,801** votes. 

	![alt text](https://github.com/Karenjakins/Election_Analysis/blob/main/Resources/County%20Votes%20Information.png "County Votes Information")

- The running candidates and the results per candidate can are listed below and can also be referenced on the screenshot below:

	- Diana DeGette received **73.8%** of the vote which is **272,892** votes, was the **winner of the election**. 
	- Charles Casper Stockham received **23.0%** of the vote which are **85,213 votes**.
	- Raymon Anthony Doane received **3.1%** of the vote which are **11,606 votes**.

	![alt text](https://github.com/Karenjakins/Election_Analysis/blob/main/Resources/Candidates%20and%20Election%20Results.png "Candidates and Election Results")

## Election Audit Summary 

The code developed to run this analysis is a great and efficient tool for the election commission to analyze data sets of big scales, like this audit, the code is extremely customizable and can be easily run to analyze any data set by making small adjustments. The script can be applied to any electoral tabular dataset simply by changing the source of the data on the code itself, as can be seen in the screenshot below. 

![alt text](https://github.com/Karenjakins/Election_Analysis/blob/main/Resources/File%20for%20analysis.png "File for analysis")

As can be seen in the following image, it's very easy to manipulate the script to be run for any sort of election, be it a congressional or even a federal election, as it was designed to pull the candidates from the dataset itself. On the second screenshot, it can also be referenced how the input for the county could be switched to a city, or even a state and the code can be easily modified to gather this data on its own as opposed to being manually entered shows how flexible and usable this code can be for the commission.

**Candidate Field easily modifiable**
![alt text](https://github.com/Karenjakins/Election_Analysis/blob/main/Resources/Candidate%20Field.png "Candidate Field")

**County can be switched to modify the target regions**
![alt text](https://github.com/Karenjakins/Election_Analysis/blob/main/Resources/County%20Field.png "County Field")

## Resources

**Data Source:** election_results.csv

**Software:** Python 3.6.1, Visual Studio Code, 1.38.1