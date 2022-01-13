Python Challenge Analysis
Election Results Audit

Part 1 – Overview of Project

The purpose of this project is to help Tom tally and audit the final election results for the Colorado Congressional precinct. As we worked side by side throughout module 3, we learned that the votes were counted using three methods:

•	Mail in Ballots – Hand counted at central office
•	Punch Cards – Collected and fed into a machine to be counted
•	Direct Recording Electronic – Read and counted by a computer

Throughout this project, a combination of for loops, conditional statements, membership operators and logical operators have been used to derive the following information:

•	Voter turnout for each county
•	The percentage of votes from each county (out of the total vote count)
•	County with the highest turnout

 The typical platform of choice for a project of this magnitude is excel. However, our client’s management would like to take things a step further to see if the process can be automated. This is where our use of Python comes in. Upon the success of this project, our code will be used to audit other congressional districts, senatorial districts, and local elections. 

Part 2 – Election Audit Results

•	Total Number of Votes Cast: 369,711

County	Vote Count	Vote Percentage
Jefferson	38,855	10.5%
Denver	306,055	82.8%
Arapahoe	24,801	6.7%

•	County with Highest Vote Count: Denver (306,055 votes; 82.8% of total)

Candidate	Vote Count	Vote Percentage
Charles Casper Stockham	85,213	23.0%
Diana DeGette	272,892	73.8%
Raymon Anthony Doane	11,606	3.1%


•	Winning Candidate: Diana DeGette (272,892 votes; 73.8% of total)

Part 3 – Election Audit Summary

A point was made throughout this project to ensure that the code can be applicable for any election with only small modifications. The code structure does not need to be altered. However, it will be necessary to adjust it to suit the election at hand. Below, I’ve outlined two examples of how the code can be modified for a different election. 

Example 1: 

The portion of the code outlined in red was put in place so that any coder can ensure there’s no data that already matches something existing. In this case, we are cross checking to ensure that there are no counties that match any of the existing counties in the list. Replicas could lead to skewed results. 

  

Say we are auditing a senatorial election and hence are dealing with districts as opposed to counties. One could alter the “county_name” to be “district_name.” This would be a small change that would serving a significant purpose.

Example 2:

The code below depicts the if statement that was written to determine the winning county along with its vote count. 
 

If this code was being used in a different election, it would be imperative to make sure the variable defining the winning count is written appropriately for the election at hand. That means that not only would it need to be altered in the code depicted here, but throughout the entire code we would need to have that “winning_ccount” portion defined appropriately which began at step 2. 
![image](https://user-images.githubusercontent.com/94502363/149250757-4d538929-456d-4963-ac7a-c6da3ec3abb2.png)
