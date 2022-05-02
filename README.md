# election_analysis
Analysis of election results using Python
# Overview of Election Audit

The purpose of this project is to report the results of the election for U.S Congressional Precinct in Colorado. The code written will be helping to report the total number of votes cast, the total number of votes for each candidate and county, as well as the percentage of votes for each candidate and county. This code will be used to help automate the generation of election results in other elections as well.

# Election-Audit Results

### Break Down- County

* 369,711 votes were cast in the entire election. 
* These votes came from 3 counties: Denver, Arapahoe, and and Jefferson. 
* Jefferson county generated 38,855 votes which accounted for 10.5% of the votes. 
* Arapahoe county generated 24,801 total votes which accounted for 6.7% of the vote.
* Denver county generated 306,055 votes which accounted for 82.8% of the vote.

Through this data we can tell that Denver had the highest voter turnout and generated the most votes by a wide margin.

### Break Down- Candidate

* The election featured 3 candidates: Charles Casper Stockholm, Diana DeGette, and Raymon Anthony Doane. 
* Charles Casper Stockham generated 85,213 votes which accounted for 23% of the vote. 
* Raymon Anthony Doane generated 11,606 votes which accounted for 3.1% of the vote. 
* Diana DeGette generated 272,892 votes which accounted for 73.8% of the vote.

### Winning Candidate
After the election, Diana DeGette was the winning candidate. Diana generated 272,892 votes. This accounted for 73.8% of the total votes.
# Election-Audit Summary

Although this code was tailor made for this specific election, it can recycled for any other elections as well with some slight modifications. In order for us to do this, we would need to edit the data source. In our code we used the "election_results.csv" file to retrieve data for our code to cycle through. To analyze other election data We would simply need to edit this data source in the code. 

file_to_load = os.path.join("*Folder*", "*Data Source Name*")

With these new data files, however, we would need to potentially edit the index numbers that were used to pull the candidate names and different counties. This depends entirely on the dataset and the values in the lists that are generated from the new CSV file, however. If different election data has some additional information within it, we would just have to see where the candidate name and county are located within the list. Once we figure that out, we can understand what index value to put into the code.

Get the candidate name from each row.
  
  candidate_name = row[x]

Extract the county name from each row.
   
   county = row[y]
