# Assignment
# Question 1

The aim of this coding challenge is to create a program that checks whether a given string is a palindrome or not, irrespective of case. 
A palindrome is a string that reads the same backward as forward.
For example, "racecar" is a palindrome because it reads the same way forward and backward. 
The solution involves converting the given string to lowercase and then comparing it to its reverse. 
If both are the same, then the given string is a palindrome

# Question 2

This program counts the number of times a given substring occurs in a given string, assuming a left-to-right traversal. 
 How to use To use this program, you need to run the substring_counter.py file with Python 3. 
You will be prompted to enter a string and a substring, which can include spaces and special characters. The program will then count the number of times the substring appears in the string and print the result to the console.

# Question 3

Rock Paper Scissors Game This is a basic rock paper scissors game where two players can input their choices of either rock, paper, or scissors. The game runs for 10 rounds and declares the winner based on the rules of the game.

Rules of the Game - Rock beats Scissors - Paper beats Rock - Scissors beats Paper 
 Usage To run the game, simply execute the rock_paper_scissors.py file in your terminal or IDE. The script will prompt the two players to enter their choices for each round. Example: Enter Player 1's choice (R/P/S): R Enter Player 2's choice (R/P/S): S Player 1 wins! Enter Player 1's choice (R/P/S): P Enter Player 2's choice (R/P/S): P Draw! ... Final Winner: Player 1 The final winner is determined based on the number of rounds won by each player. If there is a tie, the game will declare a draw

# Question 4
API to print Bitcoin price in USD and GBP This API retrieves real-time Bitcoin price data in USD and GBP from the coindesk.com API. The data is collected every 5 minutes for a duration of 1 day. It ensures that consecutive data points have different.
Once you have your API key, you can use it to access the real-time Bitcoin price data in USD and GBP. 
### Installation To use this API, you will need to make a GET request to the following URL:
https://api.coindesk.com/v1/bpi/currentprice This will return the current Bitcoin price data in JSON format. ### Usage To access the Bitcoin price data using this API, simply make a GET request to the above URL with your API key included in the request headers. You can then parse the JSON-formatted data to retrieve the Bitcoin price in USD and GBP.
