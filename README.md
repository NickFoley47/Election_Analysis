# Election_Analysis

## Project Overview
The purpose of this election audit analysis was to add data requested by the election commission. The election commission requested the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout.  

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Calculate voter turnout for each county.
6. Calculate percentage of votes from each county. 
7. Calculate the county with the highest turnout. 
8. Determine the winner of the election based on popular vote.

## Resources
-Data Source: election_results.csv

-Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- County vote information:
	- Jefferson: Had 10.5% of votes and 38,855 votes casted.
	- Denver: Had 82.8% of votes and 306,055 votes casted.
	- Arapahoe: Had 6.7% of votes and 24,801 votes casted.

Code snippet to determine county percentage of votes:

![Code for County Percent](https://github.com/NickFoley47/Election_Analysis/blob/main/Resources/Code%20for%20County%20Percent.PNG)

Code snippet to determine to total county votes:

![Code for total county votes]( https://github.com/NickFoley47/Election_Analysis/blob/main/Resources/Code%20for%20total%20county%20votes.PNG)

Code snippet for highest county turnout:

![Code for highest county turnout]( https://github.com/NickFoley47/Election_Analysis/blob/main/Resources/Code%20for%20highest%20county%20turnout.PNG)

### County with largest turnout:
- Denver had the largest number of votes which was 306,055 and had 82.8% of total votes.

### Candidate Infomation: 
- The candidates were:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane 
- The candidate results were:
	- Charles Casper Stockham received 23% of the vote and 85,213 votes.
	- Diana DeGette received 73.8% of the vote and 272,892 votes.
	- Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
	
	
Snippet of election results:

![Election Final results](https://github.com/NickFoley47/Election_Analysis/blob/main/Resources/Election%20Final%20results.PNG)

Code snippet to determine candidate votes and percentages:

![Code for candidate votes and percentage]( https://github.com/NickFoley47/Election_Analysis/blob/main/Resources/Code%20for%20candidate%20votes%20and%20percentage.PNG)

### Winner of Election:
- The winner of the election was: Diana DeGette who received 73.8% of the vote and 272,892 votes.  


Code snippet to determine winner:

![Code for candidate winner]( https://github.com/NickFoley47/Election_Analysis/blob/main/Resources/Code%20for%20candidate%20winner.PNG)



## Election-Audit Summary:
Election commission this script we have created for the current election can be modified for any elections you may need assistance in the future. Python is a powerful tool where we can pull data from any excel csv file and evaluate election results. The committee can access CSV data by just fixing the path where you want the data from and then the data will be pulled from that CSV.

Code snippet for path to CSV file:

![How script can be reused]( https://github.com/NickFoley47/Election_Analysis/blob/main/Resources/How%20script%20can%20be%20reused.PNG)

Code snippet to pull data from CSV file: 

![How script can be reused part 2](https://github.com/NickFoley47/Election_Analysis/blob/main/Resources/How%20script%20can%20be%20reused%20part%202.PNG)

