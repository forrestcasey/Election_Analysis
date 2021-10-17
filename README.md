# Election Analysis: Deliverable 3

## Project Overview

A Colorado Board of Elections employee gave the following tasks to complete the election audit of a recent local congressional election.

 The data to retrieve: 
 1. The total number of votes cast
 2. A complete list of candidates who received votes
 3. The percentage of votes each candidate won
 4. The total number of votes each candidate won
 5. The winner of the election based on popular vote

The purpose is to count, collect & summarize the data in the csv file into
a logical and concise format in order to read the results of the election.

## Results

The analysis of the election shows that:

* There were 369,711 total votes cast in the election.
	- Jefferson county had 10.5% of the vote for a total of 38,855 votes
	- Denver county had 82.8% of the vote for a total of 306,055 votes
	- Arapahoe county had 6.7% of the vote for a total of 24,801 votes

### Of all three counties, Denver had the largest number of votes.

* The candidates were:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane

* The candidate results were:
	- Candidate Charles Casper Stockham received 23.0% of the vote and 85,213 votes
	- Candidate Diana DeGette received 73.8% of the vote and 272,892 votes
	- Candidate Raymon Anthony Doane received 3.1% of the vote and 11,606 votes

* The winner of the election was:
	- #### Diana DeGette, who received 73.8% of the vote and 272,892 votes.



![PyPoll_Results](https://github.com/forrestcasey/Election_Analysis/blob/main/PyPoll_Results.png)





## Election-Audit Summary:

* The code can be used to count ballots and return the results to a text file for any election if the votes and candidates were provided in the same format.

* The code can be run for state-wide or country-wide elections instead of for each county.

* Adjusting variable names, row and column locations in the code, as well as file path locations, are simple enough modifications to suit the needs of the .csv file containing the data. 

## Resources

* Data Source: election_results.csv
Software: Python 3.7.6, Visual Studio Code, 1.60.2
