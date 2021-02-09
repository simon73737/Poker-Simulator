# Poker-Simulator

Program which runs a given number of simulations of 5-handed Texas Hold'em

Class Poker_Driver is used as the front end of the project
Uses a given number from the user and runs that many simulations
The Deck, Hand, and Card classes are used to build a hand for a theoretical player

The hands are then given to the Game class which plays out the rest of the game and determines the winner
The results of each game are given to the Data_Collection class which stores and updates data as the simulations continue
Once all simulations are completed, the Data_Collection method calculates certain information and prints out the reults to a text file, Results.txt
