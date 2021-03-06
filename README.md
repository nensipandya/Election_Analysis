# Election_Analysis

## Purpose of the project

Python is one od the most popular programming languages. Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built in data structures, combined with dynamic typing and dynamic binding, make it very attractive for Rapid Application Development. Python's simple, easy to learn syntax emphasizes readability. Python supports modules and packages, which encourages program modularity and cod resuse. The python interpreter and the extensive standard library are available.

## Purpose of the Election Analysis
A Colorado Board of Election committee wants me to do analysis on the election audit and complete the election audit of a recent local congressional election.  The purpose of this analysis  is to generate a vote count for the election audit  and report to the Colorado Board of Elections.

In this analyis , we need to deliver the following information:
  
   1. Total Number of votes cast
  2. A complete list of candidates who received votes
  3. Total number of votes each candiadate received
  4. Percentage of votes each candiadate won
  5. Percentage of votes of each county
  6. The highest county turnout, who recieved highest number of votes
  7. The wimnner of the Election based on popular votes.

## Resources
- Data Source: election_results.csv
- Software : 
    - Pythond 3.7.3
    - Visual Studio Code 1.47.3

## Summary
The analysis of the election shows that:

 - There were 368,711 votes cast in the election.
 - The candidates were:
   1. **Charles Casper Stockham**
   2. **Diana DeGette**
   3. **Raymon Anthony Doane**
  - The candidate results were:
   1. **Charles Casper Stockham** received **23.0%** of the vote and **85,213** number of votes.
   2. **Diana DeGette** received **73.8%** of the vote and **272,892** number of votes.
   3. **Raymon Anthony Doane** received **3.1%** of the vote and **11,606** number of votes.
  - The county votes were:
   1. Jefferson county received 10.5% of the vote and 38,855 number of votes.
   2. Denver county received 82.8% of the vote and 306,055 number of votes.
   3. Arapahoe county received 6.7% of the vote and 24,801 number of votes
  -  The highest numbers of votes had been received by the **Denver** county.
  -  The winner of the election was **Diana DeGette** , who received **73.8%** og the vote and **272,892** number of votes.
  
  
  
  
<img width="239" alt="Election_Results" src="https://user-images.githubusercontent.com/107137215/177399237-75d09194-96d6-4a1c-8bea-4cb528b8ec34.png">


## Election - Audit Summary
Elaborating the Election Audit by county turnout has been a great way to take advantage of the python scripts. This added insight can be very helful for the future election performance , where we are able to to find out demographoce turnout for each an individual candidate.

A minor modification in the scripts can reveal critical data. For example, we can dive- in deeper in the analysis and able to determine what percentage of each county voted for each candidate just by addinf -if statement to the code.

Similarly, we can use the same code for the Federal Election and instead of couty, we are able to to find out percentage of vote for each states.

In short, whether it is a state / federal election, county or candidiate vote percentage, the python code  is very useful and valuable resources for the Election Board.
