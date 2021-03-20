# 8-quuen-problem-using-Hill-Climbing
AI project

 	Project Title: 
Solve 8 Queens problem using hill-climbing algorithm with the help of C/C++ programming language. Initial configuration of the problem is given below:

 



 	


 	Abstract:-
8-Queen Problem is a classical puzzle of placing mutually non-attacking 8 queens on 8 by 8 board and is very popular among researchers.  This  problem  has become  very  useful  in  the  recent  past  for  the  scientists because of having many applications in the real world. In this project we propose this as a game and implement using hill-climbing algorithm with the help of C/C++ programming language to get to the solution. The most primitive way to solve them is "Brute-Force" - that means: Simply try everything out. The n-Queen problem become intractable for large values and thus placed in NP (non-deterministic polynomial) class problem. The n-Queen problem is basically a generalized form of 8-Queen problem. The solution can very easily be extended to the generalized form of the problem for large values.


 	Introduction:-

8-Queen Problem is placing 8 queens on an 8 by 8 chessboard so that according to the allowed moves of the queen(Queen can move in any direction i.e. row, column and even diagonally crossing as many squares as it can or have to),none of the Queen is under attack.  Problem can be best understood as follows: 
•	Each row can have only one queen.
•	Each column can have only one queen.
•	There can be maximum only one queen on a diagonal at a time.
•	Since the board is symmetric, reflection and rotation can be applied to get solution from known solutions.



 8-Queen problem is very expensive to compute because there are all in all 64! = 4.4 x 10^9 [2] total number of possible arrangements of queen. There are 12 unique solutions for an 8 by 8 chessboard and 80 other distinct solutions obtained by rotation and reflection property, summing up to 92. This problem is belongs to special category of problems (NP hard) because its solution cannot be found out in polynomial time. One of the solutions is given below.
 
 

8-Queen puzzle has many applications in scientific and engineering field such as VLSI testing and routing, traffic control, maximum full range communication, parallel optical computing, parallel memory storage schemes, deadlock prevention. Machine learning is one of the most fascinating areas of Artificial Intelligence. It is basically the study of building computer systems which adapt and improves with its experience. Most of the problems of data acquisition are solved by machine learning.













 	Algorithm:-
Hill Climbing Search
(Steepest Ascent/Descent)
• At each iteration, the hill-climbing search algorithm moves to the best successor of the current node according to an objective function.
• Best successor is the successor with best value (highest or lowest) according to an objective function.
• If no successors have better value than the current value, it returns.
• It moves in direction of uphill (hill climbing).
• It terminates when it reaches a “peak” where no neighbor has a higher value.
• The algorithm does not maintain a search tree, so the data structure for the current node need only record the state and the value of the objective function.
• Hill climbing does not look ahead beyond the immediate neighbors of the current state.
• Hill climbing is sometimes called greedy local search because it grabs a good neighbor state without thinking ahead about where to go next.
• Greedy algorithms often perform quite well and
• Hill climbing often makes rapid progress toward a solution.






To understand local search, it is useful to consider the state-space landscape. 
•	The aim is to find the highest peak - a global maximum. 

•	Hill-climbing search modifies the current state to try to improve it.

•	A local maximum is a peak that is higher than each of its neighboring states but lower than the global maximum.
o	Hill-climbing algorithms that reach the vicinity of a local maximum will be drawn upward toward the peak but will then be stuck with nowhere else to go.

•	A plateau is a flat area of the state-space landscape. It can be a flat local maximum, from which no uphill exit exists, or a shoulder, from which progress is possible.

•	A hill-climbing search might get lost on the plateau. 
• Random sideways moves can escape from shoulders but they loop forever on flat maxima.


 



 
    

