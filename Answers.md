## Debugger Lab Answers
**Question 1**
cutoff is not a parameter to the method playTurn in the PigGame class because cutoff was
assigned as a parameter for all of the PigGame class, therefore you do not need cutoff in
the method playTurn because it is already assigned to the class.

**Question 2**
The code would print the average number of turns the player had inorder to reach the goal
value of 100. However the code would turn the average as 0 because Scoresheet was just 
reset.

**Question 3**
The statement numBusts coula aslo be placed into the getNumTurns method because the method
is analyzing the turns and while it is analyzing it can also return the numBusts with out 
affecting the results of the program. 

**Question 4**
I believe that the error in the code might be in the playTurn method, or playGame method. 
I don't think that there could be problems in the code in the method PigGame.

**Question 5** 
There is something wrong with the dice because when I went through the debugger dice
rolled a 1 three times in a row. I found that thee was something wrong in the formatting 
to roll the dice. With this change the program now returns the correct score, number of 
turns, and turn average.

**Question 6**
The average number of turns for the cutoff value of 10 is 6.25.The average number of turns
for the cutoff 15 is 7.6923076923076923. The average number of turns for the cutoff 20 is
6.666666666666667. The average number of turns for the cutoff 25 is 6.0588235294117645.
