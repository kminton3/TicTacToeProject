# TicTacToeProject Description
A TicTacToe game I made from a tutorial last summer to practice Java.

# Author 
Kylie Minton

# About "TicTacToe"
	
	This project, though common in programming courses, was one I did on my own. 
	I find that Java is a difficult language for me, so I decided to follow an online tutorial to create a tictactoe game!
	My program does not require the use of any external applications to run, as it can be run from the command line.
	I finished this project in a week, spending about two hours each day. 
	Even though it isn't visually pleasing to look at, I'm very proud of it and hope to revise it someday to make it look prettier and work better.


# How to Play
	Player One is assigned the token 'X', and Player Two is assigned the token 'O'.
	Each player will type a number that corresponds to a number 1-9 on the tictactoe board and press enter.
	Once they have entered their choice, they will see their respective token on the board where the number was. 
	If this number is chosen again, they will recieve an error and be asked to choose a different number.
	The game ends when all spaces are filled and either one player has won or a tie has occurred.
	
	*Tip: I have personally found that if you attempt to position three of your tokens in three of the corners, you almost never lose!
	/---|---|---\
	  x       x
	|-----------|

	|-----------|
 	  x
	/---|---|---\

# Known Issues: 
	Lines 36-38 are meant to generate an error if characters other than 0-9 are entered. 
	Currently, the program loops infinitely. 
	My temporary fix, which I hope to fix in my spare time, is to implement "break;".

