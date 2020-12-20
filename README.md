# Py_PollChallenge

## Overview of Election Audit
The purpose of this election audit was to submit additional data to the election commission specifically for voter turnout in each county, percentage of votes from each county from the total vote, and show the county with the highest turnout.

## Election Audit Results 
* Exactly 369,711 votes were cast in this congressional election. [This is the code used to be able to print and see clearly how many votes were cast.](https://github.com/LaurenSonis/Py_PollChallenge/blob/main/2020-12-20%20(1).png)
* Jefferson County had 10.51% of the votes with 38,855 votes cast. Denver County had 82.78% with 306,055 votes, and Arapahoe County had 6.71% with 24,801 votes cast. [This is a for loop written to see what percentage of the vote each county had.](https://github.com/LaurenSonis/Py_PollChallenge/blob/main/2020-12-20%20(2).png)
* Denver County had the largest number of votes.
* Diana DeGette had 73.8% of the vote with 272,892 votes cast. Charles Casper Stockham had 23.0% of the vote with 85,213 votes cast, and Raymon Anthony Doane had 3.1% of the vvote with 11,606 votes cast. [This is code written to see how each candidate fared.](https://github.com/LaurenSonis/Py_PollChallenge/commit/bf1c446d2a352ba45239ca3fbf5976bd5b911288)
* Diana DeGette won the election with 73.8% of the vote and 272,892 votes cast.

## Election Audit Summary
I propose that this script could be used, with modifications when needed, for any election. For example, the commission could use this script for a gubernatorial race by changing the csv file of data for one holding information on the gubernatorial race and expanding the counties list to include all of the counties in the state. Furthermore, the commission could use this script for a more localized election, such as a county sheriff's race. The commission would of course need to exchange the appropriate csv data and then change the code to reflect districts within a county versus the county itself. [For example, the commission could exchange county for district where county_list is on line 27.](https://github.com/LaurenSonis/Py_PollChallenge/blob/main/2020-12-20%20(4).png)
