# Election_Analysis

## Project Overview
Seth and Tom have asked me to help audit the results of an election for their election commission. Using a CSV file of the election results, I've been tasked with calculating vote totals and percentages broken out by county and candidate. 


## Election Audit Results

-369,711 total votes were cast in this election

-Votes and percentage of votes for each county
	-Jefferson: 38,885 votes at 10.5% of overall votes
	
	-Denver: 306,055 votes at 82.8% of overall votes
	
	-Arapahoe: 24,801 votes at 6.7% of overall votes

-Denver county has the largest number of votes

-Votes and percentage of votes for each candidate
	-Charles Casper Stockham: 85,213 votes at 23.0% of overall votes
	
	-Diana DeGette: 272,892 votes at 73.8% of overall votes
	
	-Raymon Anthony Doane: 11,606 votes at 3.1% of overall votes

-Diana DeGette won the election with 73.8% of the overall votes and 272,892 votes

![Election_Results_Terminal](https://raw.githubusercontent.com/mdwilliams11/Election_Analysis/main/Resources/Election_Results_Terminal.png)


## Summary
This analysis was performed using a python script to read through the election results CSV file.

[The python file can be found here.](https://raw.githubusercontent.com/mdwilliams11/Election_Analysis/main/PyPoll_Challenge.py)


This file could potentially be used to quickly audit future election results. Some of the code references specific columns within the CSV file so any future election would have to account for potential changes to the structure of the election results.
The CSV the code read through had three columns: Ballot ID, County, and Candidate. If you were to work with a csv election result file that had different columns, you could easily change a few references to specific columns indexes within the code to account for the difference.
The code is set up to read the different counties in the data in order to get county-specific vote counts and percentages. The code would also work if the election results were for different counties or even different states.
