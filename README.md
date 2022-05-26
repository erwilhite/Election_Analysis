# Election Analysis
## Project Overview
The purpose of this analysis was to assist a Colorado board of elections employee in an election audit of the results of a US congressional precinct in Colorado. This analysis has previously been performed in excel, but it was requested to see if it could be performed in another way to automate the process going forward. This analysis required retrieving and certifying the total number of votes, the vote split between the counties and the candidates, the largest county turnout, and the winning candidate. 

## Election Audit Results
The outcomes of the election are shown below:
•	Total Votes: 369,711
•	Votes by County:
o	Jefferson: 38,855 - 10.5%
o	Denver: 306,055 - 82.8%
o	Arapahoe: 24,801 - 6.7%
•	County with Largest Turnout: Denver
•	Votes by Candidate:
o	Charles Casper Stockham: 85,213 - 23.0% 
o	Diana DeGette: 272,892 - 73.8% 
o	Raymon Anthony Doane: 11,606 - 3.1%
•	Winning Candidate:
o	Diana DeGette: 272,892 - 73.8% 
First the code defined the variable and lists needed to perform the analysis. 

 ![Variables defined and Lists created](https://user-images.githubusercontent.com/104689576/170521216-1ade0f7d-5d64-4168-8082-46ed47970e2d.png)

Then it looped through it to tally the total votes, as well as separating the candidates and counties into their respective lists and tallying their votes. 

 ![Loop](https://user-images.githubusercontent.com/104689576/170521239-af200e12-2c32-4ff7-be79-5a8640359ef0.png)

Finally, it looped through the dictionaries to break out the keys and find their vote count, percentage of votes, and then determine the winning county and candidate.

![other loop](https://user-images.githubusercontent.com/104689576/170521257-99140064-0d28-458f-ac95-930f91e9e174.png)

## Election Audit Summary
This script provided the ability to quickly analyze more than 369,711 rows of data in a csv file, without having to manipulate it in the original file. It was done in Python by creating variables, lists, and dictionaries to loop through the data, sort it to the appropriate category, and tally up the votes. It is suggested that this script be used and modified as necessary to quickly analyze other elections, as it will save time and money in performing the data analysis. Simple modifications to allow this script to work for other elections would require changing the csv that file that contains the votes as well as changing the output txt file. 


