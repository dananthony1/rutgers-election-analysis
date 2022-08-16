# rutgers-election-analysis
Module 3 for Rutgers Data Science Bootcamp - Using Python in VS Code 

## Overview of Election Audit:
  The election audit reads an .xlsx file of election results and returns the percentage and total votes per county and per candidate. The results are also written into a file in the analysis folder. In addition the largest county and results of the winning candidate are returned. These pieces of information provide a comprehensive summary of the election results from an .xlsx format into a printed return and a .txt format for review.    

## Election-Audit Results:
* The total number of votes cast in the congressional election is 369,711.
* Jefferson County had 10.5% of the votes at 38,855 total votes.
* Denver County had 82.8% of the votes at 306055 total votes.
* Arapahoe County had 6.7% of the votes at 24,801 total votes.
* The county with the largest number of votes is Denver.
* Charles Casper Stockham received 23.0% of the votes with 85,213 total votes.
* Diana DeGette received 73.8% of the votes with 272,892 total votes.
* Raymon Anthony Doane received 3.1% of the votes with 11,606 total votes.
* Diana DeGette won the election with 272,892 votes at 73.8% of the total votes.

## Election Audit Summary:
  This script can be used to provide an overview of the voter turnout per county and the percentage of votes for each candidate. A list can be returned that shows all of the counties in the order of the highest percentage of votes to the lowest. If the data is sorted by county and candidate, we can use additional variables to track the number of votes per candidate in each county. This will be done using an if statement and conditional of whether the candidate has been added to each counties candidate list, then the number of votes is accumulated until the next candidate is reached. With this information we can decide which counties each candidate should advertise to in order to strengthen their voter base or build a following in a county.  With an additional column that includes total population information per county, a comparison can be created between the counties' turnout and their population to determine whether to advertise more heavily in an underrepresented county. 
  
