*********************# Suduko_Mini_Game*****************************
******************# Terminal_Based_Sudoku*****************************
This is my  C++ project.  
The task was to create a Terminal game with no graphics. We decided to make a text-based adventure game. 
The idea was to have multiple rooms that are locked, and to unlock them the player would have to face a challenge (a.k.a. a mini game/puzzle). 
My sudoku is one of the mini games. I also contributed to the main code, the code planning and the databases.


Filling the game with wrong numbers leads to a complete restart(as designed), but when completing the game correctly the game does not finish, 
it restarts again. After some tests I found out it was a logical error, but till today I have not found where it happen. 
The game does print the Congratulations message, but after it, the code for some reason prints the grid again, 
and if that time the grid is filled correctly (for the second time), the game closes as intended. 
I think it has something to do with the while loop inside the .hpp file. ANY SUGGESTIONS ARE WELCOME!
As of today(28.06.2021) the sudoku game is nearly finished. Debugging is in progress. Current bug case is as follows:
The while loop in the header file does not break, which leads to a state in which the player cannot enter anything, because everything is filled.
