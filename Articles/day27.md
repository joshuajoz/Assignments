 # Day27

* I Tried to solve a problem tower of hanoi ,i have learned the steps ivolved to solve the problem ,how or the ways to solve the tower of hanoi problem.
* The algorithm and constraints are ,
* Constraints
 
   - Only one disk can be moved among the towers at any given time.
   - Only the "top" disk can be removed.
   - No large disk can sit over a small disk.
* Algorithm
 To write an algorithm for Tower of Hanoi, first we need to learn how to solve this problem with lesser amount of disks, say → 1 or 2. We mark three towers with name, source, destination and aux (only to help moving the disks). If we have only one disk, then it can easily be moved from source to destination peg.

If we have 2 disks −

   - First, we move the smaller (top) disk to aux peg.
   - Then, we move the larger (bottom) disk to destination peg.
   - And finally, we move the smaller disk from aux to destination peg.

