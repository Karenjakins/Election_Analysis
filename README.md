# Election Analysis

## Project Overview

Conduct an analysis for an election audit of the Colorado Board of Elections for a recent local congressional election, to determine the winning candidate and the largest voter turnout based on county. The analysis required the follwing data to be presented:

1. The total number of votes casted.
2. The list of all candidates in the election.
3. The total number of votes received per candidate.
4. The total number of votes per county. 
4. The percentage of votes for each candidate. 
5. The winner of the election.
6. The county with the largest voter turnout. 

## Election Audit Results 

- After conducting the analysis, a total of **369,711** votes were casted during this congressional election from the counties in the precint, those being Denver, Jefferson, and Arapahoe. As can be referenced on the image below, the breakdown of the total votes per county lists Denver, the county with the largest number of votes, with an **82.8%** of the popular vote achieving a total of **306,055 votes**. The county of Jefferson received a **10.5%** of the popular vote with **38,855** votes while Arapahoe received **6.7%** of the popular vote with a total of **24,801** votes. 

	![alt text](https://github.com/Karenjakins/Election_Analysis/blob/main/Resources/County%20Votes%20Information.png "County Votes Information")

- The running candidates and the results per candidate can are listed below and can also be reference on the screenshot below:

	- Diana DeGette received **73.8%** of the vote which are **272,892** votes, was the **winner of the election**. 
	- Charles Casper Stockham received **23.0%** of the vote which are **85,213 votes**.
	- Raymon Anthony Doane received **3.1%** of the vote which are **11,606 votes**.

	![alt text](https://github.com/Karenjakins/Election_Analysis/blob/main/Resources/Candidates%20and%20Election%20Results.png "Candidates and Election Results")

## Election Audit Summary 

The code developed to run this analysis is a great and efficient tool for the election commmision to analyze data sets of big scales, like this audit, the code is extremely customazible and can be easily run to analyze any data set by making small adjustments. The script can be applied to any electoral tabular dataset simply by changing the source of the data on the code itself, as can be seen on the screenshot below. 

![alt text](https://github.com/Karenjakins/Election_Analysis/blob/main/Resources/Candidates%20and%20Election%20Results.png "File for analysis")

As can be seen on the following image, its very easy to manipulate the script to be run for any sort of election, be it a congressional or even a national election, as it was desigend to pull the candidates from the dataset itself as opposed to be manually entered this reflects how extremely felxicble and usable this code is for the commission. 

![alt text](https://github.com/Karenjakins/Election_Analysis/blob/main/Resources/Candidates%20and%20Election%20Results.png "Candidate Field")

## Resources

**Data Source:** election_results.csv

**Software:** Python 3.6.1, Visual Studio Code, 1.38.1