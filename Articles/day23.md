# Day23

* I have learned the basic of javascript ,How object and array works in a program .I have learned that array can store values of any primitive data type, so an arrays consist of strings, numbers, booleans, objects, or even other arrays. Objects are used to represent a “thing” in your code. That could be a person, a car, a building, a book, a character in a game — basically anything that is made up or can be defined by a set of characteristics. In objects, these characteristics are called properties that consist of a key and a value.

* And also i have learned that in javascript delete is something that delete one particular object.I have learned about loop ,how the while loop formed and how the loops are used,loops is the quick and easy way to do something repeatedly.The curly braces we used in a program to define the function is called blocks. I have learned to write a program by using while loop for printing the given numbers in reverse,the given number was [0,1,2,3,4,5],
program is
                let king=[0,1,2,3,4,5]
                let i=king.length-1;
                let queen=[]
                let j=0
                while(i>=0)
                {
                queen[j]=king[i]
                j++;
                i=i-1;
                }
                console.log(queen)
Algorithm:

How i done this is

* I have given the given numbers in a array.
* Then to denote and calculate the length of the given value i gave 'i'.
* To save the given number in reverse i added another empty object.
* then i gave another iteration j=0.
* In while condition ,the first iteration 'i'should be with a condition ,(i>=0)it can be assigned with different value but i have given this condition because i dont wont a loop in backwards as -1,-2... it will go as loop to a n number of value,so it should stop at 0 so that condition is given.
* Then i have opened a block inside the while condition to print.
* Then the given values should be assigned to the new object in reverse order so i have given that 'queen[j]=king[i]'.
* Then the operation should be done so i used i++ and i-- .
* To print the value console.log is used .
* then closed the opened block.
 
* Then i learned about the functions , if different amount of number is given the above operation is very difficult to perform so that we can teach the computer about the program so if we function again it will be very easy to use the function or the operation to do another calculation easily.
