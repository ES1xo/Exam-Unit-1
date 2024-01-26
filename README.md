# Exam Unit 1
 For this exam, we were given 5 tasks with the same basis of fucntions, but with different problems. 

**Task 1**

In this task, I was considering inputting the moves manually, but after some thought I realized it would not be too hard to find a way using functions to program a solution. I started with making a while loop that would run until the car reaches the goal, where if Peek is true, the car will Move, but if Peek is not true it will turn until Peek i true and move forwards. The problem I encountered here was when the car could not immediately turn right and continue it could end up turning around completely and going backwards, as in turn 2 for example. For this reason I added a counter if Peek was not true for 2 or more times in a row, to make sure this would not happen and it would continue forward without backtracking in the left turns.

**Task 2**

This task was relatively simple as the car just had to turn right always, so I only needed the simple logic I started task 1 with, for it to get out of the spiral maze succesfully.

**Task 3** 

This task was very similar to Task 1 and the same problem could be encountered there so I just used the same method as in Task 1.

**Task 4**

This task had a complicated maze and got me thinking about different solutions. I thought of only moving in a direction if Peek was true for 2 or more spaces, but found out that some parts in the maze would cause this logic to fail and the car would never be able to complete it. Then I thought about the righthandrule, but stuggled to make it work succesfully without allowing any errors. In the end I used the same logic as in Task 1 and 3 as I thougt this would be my best shot and could end up completing the maze in the end.

**Task 5**

Even though this was a smaller maze than in task 4 it was also a bit complicated, and I tried to think of different solutions here aswell, but could not find a perfect method, however I think the method I used in the previous tasks actually could work here aswell so I went with that.

