# python-challenge
This repository contains challenge files for UT DAV Bootcamp Module 3 Python

# File Notes
* PyBank folder contains all files associated with the PyBank instructions
   * PyBank/Resources contains budget_data.csv (The main.py script relies on the Resources folder being at the same level)
   * PyBank/analysis was created as part of the setup to contain the results file rather than the script creating the folder
     * PyBank_results.txt is the file created/overwritten by the main.py script containing the results
   * main.py contains the python code that executes the instructions for PyBank
* PyPoll folder contains all files associated with the PyPoll instructions
   * PyPoll/Resources contains election_data.csv (The main.py script relies on the Resources folder being at the same level)
   * PyPoll/analysis was created as part of the setup to contain the results file rather than the script creating the folder
     * PyPoll_results.txt is the file created/overwritten by the main.py script containing the results
   * main.py contains the python code that executes the instructions for PyPoll

# References
The following references were used to identify various functions used within the script:
 * freecodecamp for writing to a text file: https://www.freecodecamp.org/news/file-handling-in-python/

# Instructions

Setup
 * Inside your local Git repository, create a folder for each Python assignment and name them PyBank and PyPoll.
 * In each folder that you just created, add the following content:
   * A new file called main.py. This will be the main script to run for each analysis.
   * A Resources folder that contains the CSV files you used. Make sure that your script has the correct path to the CSV file.
   * An analysis folder that contains your text file that has the results from your analysis.
 * Push these changes to GitHub or GitLab.

PyBank Instructions

In this Challenge, you are tasked with creating a Python script to analyze the financial records of your company. You will be given a financial dataset called budget_data.csv. The dataset is composed of two columns: "Date" and "Profit/Losses".
Your task is to create a Python script that analyzes the records to calculate each of the following values:
 * The total number of months included in the dataset
 * The net total amount of "Profit/Losses" over the entire period
 * The changes in "Profit/Losses" over the entire period, and then the average of those changes
 * The greatest increase in profits (date and amount) over the entire period
 * The greatest decrease in profits (date and amount) over the entire period
 * In addition, your final script should both print the analysis to the terminal and export a text file with the results.

PyPoll Instructions

In this Challenge, you are tasked with helping a small, rural town modernize its vote-counting process.
You will be given a set of poll data called election_data.csv. The dataset is composed of three columns: "Voter ID", "County", and "Candidate". Your task is to create a Python script that analyzes the votes and calculates each of the following values:
 * The total number of votes cast
 * A complete list of candidates who received votes
 * The percentage of votes each candidate won
 * The total number of votes each candidate won
 * The winner of the election based on popular vote
 * In addition, your final script should both print the analysis to the terminal and export a text file with the results.

# Hints and Considerations
 * Consider what you've learned so far. You've learned how to import modules like csv. You’ve learned how to read and write files in various formats. You’ve learned how to store content in variables, lists, and dictionaries. You’ve learned how to iterate through basic data structures. And you’ve learned how to debug along the way. Using all that you've learned, try to break down your tasks into discrete mini-objectives.
 * The datasets for these Challenges are quite large. This was done purposefully to showcase one of the limits of Excel-based analysis. As data analysts, our first instinct is often to go straight to Excel, but creating scripts in Python can provide us with more powerful options for handling big data.
 * Write one script for each of the provided datasets. Run each script separately to make sure that the code works for its respective dataset.
 * Always commit your work and back it up with pushes to GitHub or GitLab. You don't want to lose hours of your hard work! Also make sure that your repo has a detailed README.md file.
