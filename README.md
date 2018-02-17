# PyPoll

## Purpose
This python program takes a list of votes included in election_data_2.csv and determines election results. The file contains three columns: Voter ID, County, and Candidate. It outputs a results file that includes the percentage of votes received, and total number of votes received for each candidate. The results file also specifies the winner.

## Requirements
Running this file requires python to be installed. Python 3.6.2 was used during development. This program utilizes the os, and csv libraries to read the data file and to write the results file. The data is included in the raw_data file contained within the repository.

## Running the Code
to run enter the following into the command line:
`$ python election_analysis.py`

## Results
Results can be seen in pypoll_results_summary.txt
Khan won the second election with 2218231 votes which constituted about 63% of the total votes.