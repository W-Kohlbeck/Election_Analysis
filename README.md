# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast in the election.
2. Determine which county had the largest voter turnout.
3. Get a complete list of candidates who received votes.
4. Calculate the total number of votes each candidate received.
5. Calculate the percentage of votes each candidate won.
6. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.67.0

## Summary
The Analysis of the election show that:
- There were 369,711 votes cast in the election

- Total Vote Results by County:
  - Jefferson: 10.5% (38,855 votes)
  - Denver: 82.8% (306,055 votes)
  - Arapahoe: 6.7% (24,801 votes)

- Candidates:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
  
- Candidate results:
  - Charles Casper Stockham received 23.0% of the votes with 85,213 votes.
  - Diana DeGette received 73.8% of the votes with 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the votes with 11,606 votes.

- The winner of the election was:
  - Diana Degette, wwho received 73.8% of the vote and 272,892 votes.

## Election Audit Overview
The challenge involved analyzing the [election_results.csv](https://github.com/W-Kohlbeck/Election_Analysis/blob/main/Resources/election_results.csv) file which contained 369,712 rows of data. The data consisted of three columns including the Ballot ID, County, and Candidate. In order to determine the winner of the election Python was used to write a program that evaluated the data and calculated the total votes casted, number and name of candidates, and the number of votes each candidate received. This information was then used to perform calculations within the Panda script giving the percentage of total votes each candidate received, and determined the winner of the election.

## Election Audit Summary
Utilizing Python I was able to create a script that answered all of the above tasks given by the Colorado Board of Elections employee. The script is saved as [PyPoll_Challenge.py](https://github.com/W-Kohlbeck/Election_Analysis/blob/main/PyPoll_Challenge.py) and the results can be found in a text file under the Analysis folder called [election_analysis.txt.](https://github.com/W-Kohlbeck/Election_Analysis/blob/main/Analysis/election_analysis.txt)

The python script developed may be easily modified to analyze additional election results. The code was written to allow for a much larger data set by not hard coding any county names or candidates. The script can be further modified to include additional statistics, for example how many votes each candidate received in each county, and adding district information consisting of multiple counties. 
