# python_challenge

Python Challenge

PyBank
•	This script imports and reads a .csv file that contains two data points per row: Month and Profit/Losses. The objective of this script is to generate a final analysis that will be printed inside the terminal as well as exported to a text file. The analysis contains total months, total change in profit/loss, the average change in profit/loss, the greatest monthly increase, and the greatest monthly decrease.
•	The script will loop through each row. With each loop it will do all of the following:
  o	Add to the count of total months by 1
  o	Add to the running total of Profit/Losses
  o	Check to see if the Profit/Loss for that month is either
    	Larger than the current largest increase
    	Larger than the current largest decrease
  o	If either of the above statements is true, that Profit/Loss will be saved as the largest increase/decrease, with the corresponding month being saved as its own variable as well.
•	Once the loop is complete, the average will be calculated by dividing the total change in profit/loss by the total months, rounded to the nearest cent.
•	The script will then print the results and export them to a text file named “FinancialAnalysis.txt”

PyPoll
•	This script imports and reads a .csv file that contains three data points per row: Voter ID, County, and Candidate. The objective of this script is to count every vote cast, calculate the total amount of votes (and percentage of vote) for each candidate, determine a winner, print the results in the terminal, and export the results into a text file.
•	The script will loop through each row (or vote.) Each loop will
  o	Add a vote to the overall vote total
  o	Add a vote to the corresponding candidate’s vote total
•	After the loop, four separate if statements (one per candidate) will be used to determine the winner. 
  o	Khan will be determined the winner at first without comparing their votes to any other candidate. The next three if statements will compare the other candidates votes to the current leader. The leader at the end of these four if statements is declared the winner. Any time the leader changes in these statements, the variable ‘winner_votes’ will be updated accordingly with the leader’s vote total.
•	After the if statements, the percentage of the vote for each candidate will be determined. It is calculated by dividing the amount of votes for the candidate by the total amount of votes, rounded to the nearest thousandth (the rounding is not seen in this dataset because every candidate got an even percentage of the vote.)
•	After everything else has taken place, the results of the vote will be printed in the terminal. The results will also be exported to “PollResults.txt.”
