Download Link: https://assignmentchef.com/product/solved-cop-2800-assignment-3
<br>
For this assignment, you will calculate the score of the <strong>first</strong> <strong>frame</strong> of a game of bowling.  If you don’t bowl, scoring is actually quite complicated.

There are open frames, spares, and strikes.  Here are a couple of links that will help you understand the rules: <a href="http://www.bowlingindex.com/instruction/scoring.htm">http://www.bowlingindex.com/instruction/scoring.htm</a> ,

<a href="http://www.bowlinggenius.com/">http://www.bowlinggenius.com/</a>.

Here’s the catch…  There is no input for this problem.  You will be generating the pin counts with random numbers.  Examine class Random and method, nextInt; you will find it helpful.  But, be careful.  The range of possible numbers for a particular roll may depend on the pin count for the previous roll.  Again, thoroughly study scoring before you start coding.  To reiterate, you are <strong>not</strong> to score an entire game, just the <strong>first frame</strong>.  But, sometimes that requires three rolls.

There is sample output on page 2, yours should look the same, and page 3 attempts to give a short tutorial on scoring to get you started.  Submit just the .java file. Files that do not compile will receive a grade of 0.

<strong>Note</strong>: There is no need to create additional classes for this program; your instructor’s solution is all in <strong>main</strong>.  And there are no loops.  But don’t under estimate the difficulty of this problem… it requires organization and attention to detail.  Thoroughly test your solution.

In this example, the player rolled a 2 (knocked down 2 pins out of 10) on the first roll.  That left 8 pins standing.  On the second roll, the player knocked down 4 pins.  The two scores are added together for a total of 6 points from the frame.  This is an open.










In this example, the player knocked down 4 pins on the first roll, leaving 6.  On the second roll, the player knocked down all 6, for a total of 10.  But, that’s not all, since the player got all 10 pins on 2 rolls, that’s called a spare, indicated by the ‘/’.  And the frame is scored 10 + whatever the player rolls on the next roll in the second frame, which in this case was 8, for a total frame one score of 18.







In this example, the player knocked down all 10 pins on the first roll, called a strike, indicated by the ‘X’.  In such a case, the frame score is 10 + the value of the next two rolls.  In the second frame, the player knocked down 7 pins on the first roll and 3 on the second (a spare).  So, the scoring in the first frame is 10 + 7 + 3 = 20.











