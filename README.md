# Election_Analysis

## Overview of Election Audit

Tom is an employee of the Colorado Board of Elections and he needs help in an election audit of the tabulated results for US Congressional precinct in Colorado.

Tom asked our help to extract the information needed by the Colorado Board of Elections like Total number of votes cast, a complete list of candidates who received votes, the total number of votes each candidate received, the percentage of votes each candidate won, the winner of the election based on popular vote, the voter turnout for each county, the percentage of votes from each county out of the total count and the county with the highest turnout.

## Election-Audit Results

Analysing the data we counted 369,711 votes cast in this congressional election

For for each county in the precinct we had the following result:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

So we concluded that the largest county turnout is Denver

For for each candidate in the precinct we had the following result:
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

And the winner of the election is Diana DeGette with 272,892 votes, 73.8% of all votes.


## Election-Audit Summary

In order to use this script for a mayor election, the code will have to be updated to not display county related information as it might be irrelevant for this type of election.

To use this script to audit a presidential election the code can be modified to include information about the states and summarize votes for each candidate per state and indicate the winner based on the number of votes in the electoral college for each state.