# Election_analysis

## Project Overview
A Colorado Board of Elections employess has provided election data to complete the elections audit of a recent local congressional election. The employess requested to use Python to complete the audit to automate the process. The task was to determine the winner by popular vote. Information regarding county turnout and percentage of votes were also obtained.
 

## Resources
- Data Source: election_reults.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38. 1

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The results based on county were:
    - Jefferson county had 10.5% of the votes with 38,855 votes in total. 
    - Denver county had 82.8% of the votes with 306,055 votes in total.
    - Arapahoe county had 6.7% of the votes with 24,801 votes in toal. 
- Denver county had the largest number of votes with 306, 055 votes. 
- The candidate results were:
    - Charles Casper Stockholm recieved 23.0% of the vote and 85,213 number of votes
    - Diana DeGette recieved 73.8% of the vote and 272,892 number of votes
    - Raymon Anthony Doane recieved 3.1% of the vote and 11,606 number of votes
- The winner of the election was:
  - Diana DeGette who recieved 73.8% of the vote and 272,892 number of votes. 

  ## Challenge Summary
Python code was used to analyze data provided in a .csv file of election data for a local congressional election in Colorado. The code was used to determine the winner of the election through popular vote. With the python code, vote totals for each candidate were tallied using for loops and if statements. This method was also used for tallying county turnout percentages and totals. All of the results were save into a text file for documentation. 

This same script could be modified and used in other scenarios regarding elections. If an election involved a third party with multiple candidates (as opposed to single candidates for the 2 major parties), it would be able to tally both number of votes and percentage of votes for those in the third party. This could be done by creating a new list for third party candidate names and a dictionary for votes cast for the candidates in the third party, disregarding the 2 major party candidates and their votes recieved. Then using the same for and if statements in the script for determing percentages and counts while replacing the variable names for the third party candidates, it would return the third party candidate results. 

This code could also be used, if provided the data, to determine votes based on party affiliation. Another for loop could be added to loop through the party affiliation in the data and tally for each party. A list and dictionary would need to be added with the correct variables accounting for part name and votes.  

