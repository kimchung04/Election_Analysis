# Election_Analysis
## Overview of Election Audit:
The purpose of this election audit analysis is to submit the election audit results to the election commission.
- Caculate the numner of votes cast.
- Get a complete list of candidates who receive votes.
- Percentage of votes for each county, based on total vote count.
- Determine the winner of the election based on popular vote.
## Resources:
- ​Data Source: election_results.csv
- Software: Python 3.9.1, Visual Studio Code 1.52.1
## Election Audit Results
- How many votes were cast in this congressional election?
  - Total Votes: 369,711
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  - County Votes:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- Which county had the largest number of votes?
  - Denver
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  - Winner: Diana DeGette
  - Winning Vote Count: 272,892
  - Winning Percentage: 73.8%

Colorado saw three counties tally up to 369,711 votes. The biggest of the counties with a 82.8% was Denver. We processed the votes for three candidates of Charles, Diana, and Raymon. With 73.8% of the votes towards Diana DeGette, that is 272,892 of the 369,711 total votes.

## Election audit Summary:
This script can be used for any future election because it gives us a great breakdown of counties or even states if the data was different. By changing the list of counties and candidates you can use the same layout to find results needed. The added insight can be a guide for future election performance, so that you may properly allocate resources where turnout is low or demographics are hard to reach. For example:

1. The election results file contains 3 columns. If you wanted to add a fourth column for "Political Party", we could adjust our code to display the following:
   -  votes per political party
   -  vote percentage for political party out of total votes

If this were a federal election, we could create dictionary similar to "county_list" that contains the name of the political party as the KEY, and the votes per political party as the VALUE. 
        
2. If you wanted to understand the age of the voters, we could add a column for "Age" that corresponds with each Ballot ID. This would allow you to understand the following:
   - Which age group had the most voters?
   - What age group was most responsible for the winner of the election? (Which age group did the support come from?)
