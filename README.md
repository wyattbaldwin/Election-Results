# PyPoll-Challenge

## Overview of Election Audit
The purpose of this code was to audit the results of the election and provide additional information requested by the commission. In addition to the audit they requested a voter turnout for each county, the percentage of votes from each county out of the total votes, and a record of the county with the highest turnout.

## Election Audit Results
In the election 369,711 votes were cast, the winner being Diana DeGette with 73.8% of the vote and 272,892 votes. The total vote counts for each candidate were as follows:

- Charles Casper Stockham:
    - 23.0%
    - 85,213 votes
- Diana DeGette:
    - 73.8%
    - 272,892 votes
- Raymon Anthony Doane:
    - 3.1%
    - 11,606 votes

Additional data that was requested by the commission on the county vote totals:

- Largest voter turnout: Denver county
    - 82.8%
    - 306,055 votes
- Jefferson county
    - 10.5%
    - 38,855 votes
- Arapahoe county
    - 6.7%
    - 24,801 votes

## Election Audit Summary
The code for this audit can be generalized for use in future elections with the use of relative file paths and so long as the results provided are from a similar csv file. The use of for and with statements to loop through the rows should hold under these conditions. However, if you wish to use different file names you will need to update the code to change the load refrence or save prefrence. Other options that may be desireable would be an addition to the save file that uses the current date as the date for the file to differentiate versions.
