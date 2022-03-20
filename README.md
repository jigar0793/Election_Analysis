# Election_Analysis

## Analyze Elections results using Python

Now that you have seen the given dataset, you're going to sit down with Tom to go over the tasks that need to be completed for the election audit, and discuss the information needed by the Colorado Board of Elections.

In this project, our final Python script will need to be able to deliver the following information when the script is run: 

    * Total number of votes cast
    * A complete list of candidates who received votes
    * Total number of votes each candidate received
    * Percentage of votes each candidate won
    * The winner of the election based on popular vote

Pseudocode will make the audit easier to present to nontechnical colleagues and stakeholders.

## Project Overview

A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

    1) Calculate the total number of votes cast.
    2) Get a complete list of candidates who received votes.
    3) Calculate the total number of votes each candidate received.
    4) Calculate the percentage of votes each candidate won.
    5) Determine the winner of the election based on popular vote.

## Resources

Data Source: election_results.csv
Software: Python 3.10.3, Visual Studio Code 1.65

## Analysis & Challenges:

### Deliverable 1a - Candidate Results:

#### 1. Total Votels in Election

   <img width="309" alt="image" src="https://user-images.githubusercontent.com/94248676/159175513-878a99f6-a388-40e8-be9b-319a42dd9fd7.png">

#### 2. Each Candidate's Total Votes & Percentage of Votes:

   <img width="322" alt="image" src="https://user-images.githubusercontent.com/94248676/159175146-a6c907d8-969e-475e-bd96-3fb7863abc1b.png">


#### 3. The Winner of the Election, Winning Vote Count & WInning Percentage of Votes:
   
   <img width="348" alt="image" src="https://user-images.githubusercontent.com/94248676/159175169-2a20948d-898e-49f0-a092-a69a33715507.png">


### Deliverable 1b - County Results:

#### 1. Each County with its Total Vote Counts & Percentage:
   
   <img width="305" alt="image" src="https://user-images.githubusercontent.com/94248676/159175206-be57d4cc-e819-4766-b381-69b45ebdc92d.png">


#### 2. The County with the Largest Number of Votes:
   
   <img width="292" alt="image" src="https://user-images.githubusercontent.com/94248676/159175267-d12a0c45-3e8d-438c-9890-95dec065768c.png">


### Deliverable 2 - Election Candidate Results Saved to a Text File:

#### Election Coutny Results are Saved to Text File
   
   <img width="382" alt="image" src="https://user-images.githubusercontent.com/94248676/159175306-39f2a507-538d-497c-9369-010cecc9829e.png">

### Deliverable 3: Analysis of Election Audit

#### Overview of Election Analysis:

The purpose of this project was to find out which county in Colorado State got largest vote counts. In this, we learned mostly how to read .csv files in python and learn various skills about how to analyse large data set with coding in python.

#### The analysis of the election shows:

1. Total Number of Votes in Election is 369,711

2. Canadidate Percentage of votes:
    
    * Charles Casper Stockham has 23.0% of votes with (85,213) total vote counts.   
    * Diana DeGette has 73.8% of votes with (272,892) total vote counts.
    * Raymon Anthony Doane has 3.1% of votes with (11,606) total vote counts

3. County votes:
    
    * Jefferson has 10.5% of votes with (38,855) total vote counts
    * Denver: 82.8% of votes with (306,055) total vote counts
    * Arapahoe: 6.7% of votes with (24,801) total vote counts

4. County with largest number of Votes is Denver County with 82.8% of votes with (306,055) total vote counts

5. Election Results:

    * Winner: Diana DeGette
    * Winning Vote Count: 272,892
    * Winning Percentage: 73.8%

#### Election Audit Summary:

By performing this script we can come to a point where we can analyze which county had largest votes in its state. And also which candidate received maximum votes. This script could be used in and election and easy to analyze any data within couple of seconds for eg:

    1) They could add any counties or candidates names in lists.

    2) by adding more data to list will help any analyst to visulize the results in detail version like total number of votes, County     votes, Largest county Turnouts, Canadidates lists & winner with vote count as well as percentage count. 
