# Election Audit

## Project Overview
A Colorado Board of Elections employee gave us the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get the complete list of counties where voting was held.
3. Calculate the total number of voter turnout for each county.
4. Calculate the percercentage of voters who voted within each county.
5. Determine the county with the highest voter turnout.
6. Get the complete list of candidates who received votes.
7. Calculate the total number of votes each candidate received.
8. Calculate the percentage of votes each candidate won.
9. Determine the winner of the election based on popular vote.

## Resources
- Data source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Results:
The results of this election audit show that:
- There were 369,711 votes cast in the election.

- The counties which held voting were: Jefferson, Denver & Arapahoe.
- Voter turnout for each county was:
  - Jefferson had 10.5% of voters with a voter turnout of 38,855 people.
  - Denver had 82.8% of voters with a voter turnout of 306,055 people.
  - Arapahoe had 6.7% of voters with a voter turnout of 24,801 people.
- The county with the highest turnout was therefore:
  - Denver, who received 82.8% of the voter turnout and 306,055 people.

- The candidates in the election were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidates results were:
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Summary
This code can be reused to audit results from other elections, simply by updating the data source file. It can be done by either replacing the data within the "election_results.csv" file itself, or by adjusting the file path in the line: file_to_load = os.path.join("Resources", "election_results.csv") and redirecting it to a different file.

## Challenge Overview
The challenge was to use Python to extract data, perform calculations and display results both in the Terminal and by saving the results on a Text file.

## Challenge summary
The challenge was to put in practice new skills in Python. Several things were new:
  1. Reading a CSV file to extract the data.
  2. Running calculations for both, counties and candidates.
  3. Determining the winning candidate and the county with the highest turnout.
  4. Displaying the results  
  5. Writing the results onto a new Text file
