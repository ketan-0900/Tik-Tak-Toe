Project Report on Tic Tac Toe Game:
Index:
1.	Introduction
2.	Overview
3.	Algorithm 
4.	Reference
5.	Improvements
Introduction:
This project is to implement the Tic-Tac-Toe game. It is designed with HTML, CSS, and JavaScript. The application easily opens on the browser. JavaScript is a text-based programming language used both on the client-side and server-side that allows you to make web pages interactive. Where HTML and CSS are languages that give structure and style to web pages, JavaScript gives web pages interactive elements that engage a user.
The project is to implement the Tic-Tac-Toe game which will features like
•	Single player mode (against computer i.e. AI)
•	Two player mode (against human competitor)
In single player mode, game theory logics like minimax algorithms are used to determine the best move that the computer plays.
To play the game, just click on – https://ketan-0900.github.io/Tik-Tak-Toe/
Github Link- https://github.com/ketan-0900/Tik-Tak-Toe
Algorithm:
First of all we need to implement the best move logic for the computer to play in single player mode. As already stated we have used minimax algorithms to determine the best move. 
Minimax Algorithm: 
It assumes that the players take alternate moves. It assumes player 1 as max player and player 2 as min player. The first player's (MAX's) goal is to select a move that maximizes the utility function. The second player's (MIN's) goal is to select a move that minimizes the utility function (hence the name of the algorithm).  It uses a utility function whose values are good for player 1 when they are big and whose values are good for player 2 when the values are small. Thus, it maximizes the utility under the assumption that the opponent will play perfectly. 
•	Time Complexity :  O(n^m) 
•	Space Complexity : O(nm)
where n is the number of legal moves at each point and m is the maximum depth of the tree.
 
Overview:
 
Reference:
•	https://www.geeksforgeeks.org/implementation-of-tic-tac-toe-game/
•	https://towardsdatascience.com/how-a-chess-playing-computer-thinks-about-its-next-move-8f028bd0e7b1?gi=85496df44993
•	https://www.geeksforgeeks.org/minimax-algorithm-in-game-theory-set-1-introduction/
•	https://www.javatpoint.com/ai-alpha-beta-pruning
Improvements:
1)	This project uses minimax algorithm but it can also be implemented using alpha-beta pruning, which is a modified and optimised version of minimax algorithm. This technique computes the correct minimax decision without checking each node of the game tree. This involves two threshold parameter Alpha and beta for future expansion. The two-parameter can be defined as:
a.	Alpha: The best (highest-value) choice we have found so far at any point along the path of Maximizer. The initial value of alpha is -∞.
b.	Beta: The best (lowest-value) choice we have found so far at any point along the path of Minimizer. The initial value of beta is +∞.
2)	This project allows players to play over one system but not over the internet. I’m still working on it so that players, around the globe could connect using a link.



