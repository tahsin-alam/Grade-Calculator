# Grade-Calculator

## PART 1 Simple Command Interpreter

Write a special simple command interpreter that takes a command and its arguments. This interpreter is a program where the main process creates a child process to execute the command using exec() family functions. After executing the command, it asks for a new command input (i.e., parent wait for child). The interpreter program will get terminated when the user enters quit.

---------------------------------------------------------------------------------------------------------------
In Part 1, we will work on writing a program which will take a command and its arguement and it will return assocaited functionality within that command. For example, for ls will return all files and all other things located in that folder. 

### In Linux Terminal

## PART 2 Average Grade Calculator
There are 10 students enrolled in a course. The course covers x number of chapters from a textbook (x > 1). In each chapter y number of homework(s) are assigned (y ≥ 1). The average grade for each homework in all the chapters need to be found out.
To solve this, write program which has the main process as Director process, which reads a file containing grades of all homeworks of all chapters and creates x number of Manager processes. Each Manager process will take care of solving a chapter. Each manager process will create y number of Worker process and pass one homework to each of them and they calculate and print the average.
The input file should contain the data according to the value of x and y. For example, the input text file and the process tree for x = 2 and y = 2 will look like the following:
