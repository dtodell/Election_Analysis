# Election_Analysis


The purpose of this election analysis audit is well defined. (3 pt)
Election Audit Results

There is a bulleted list where each election outcome is addressed. (7 pt)
Election Audit Summary

There is a statement to the election commission that explores how this script can be used for any election, with two examples for modifying the script. (4 pt)



Overview of Election Audit: The purpose of this election analysis is to calculate the votes per county and per candidate and ultimately determine who the winner of the election is.


Election-Audit Results:

--------------------

How many votes were cast in this congressional election?

369,711 votes

--------------------

County percentage and number of votes:

Arapahoe: 6.7% (24801 votes)
Denver: 82.8% (306055 votes)
Jefferson: 10.5% (38855 votes)

--------------------

Which county had the largest number of votes?

Denver County had the most votes with 306,055 votes.

--------------------

Candidate percentage and number of votes:

Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

--------------------

Winning candidate, percentage and number of votes:

Diana DeGette won the election with 73.8% of the votes (272,892)

--------------------

Election-Audit Summary: 

Thank you for reading this election analysis. This code can be modified for use in future elections with any number of voters, simply by following the steps below:

1. Exchange the file names and file paths (if necessary) to ones with relevant data.

2. Define the contents of the county_list list and update the county_votes dictionary to reflect the new counties.

3. Expanding scope:

If there are multiple layers of elections happening, i.e. from local, to statewide, to national, for example, or if it's going from popular vote to electoral college, as exists in the United States, then this code can be used in parallel at the lower levels, then the results can be combined into a separate election for the next level. For example, localized elections happen to elect electoral college, then electoral college can use this method to determine the President. Or we can do ranked choice voting, making all parts of the government more efficient, and make 90% of Americans much happier, but that would make the code more complicated.

--------------------