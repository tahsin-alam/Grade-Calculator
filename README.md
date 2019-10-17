# Grade-Calculator

## PART 1 Simple Command Interpreter

Write a special simple command interpreter that takes a command and its arguments. This interpreter is a program where the main process creates a child process to execute the command using exec() family functions. After executing the command, it asks for a new command input (i.e., parent wait for child). The interpreter program will get terminated when the user enters quit.

In Part 1, we will work on writing a program which will take a command and its arguement and it will return assocaited functionality within that command. For example, for ls will return all files and all other things located in that folder. 

###  Linux Terminal
<img width="862" alt="Capture" src="https://user-images.githubusercontent.com/36938994/66974403-f63d7a80-f068-11e9-9fc2-623180f45aa5.PNG">

---------------------------------------------------------------------------------------------------------------
## PART 2 Average Grade Calculator
There are 10 students enrolled in a course. The course covers x number of chapters from a textbook (x > 1). In each chapter y number of homework(s) are assigned (y ≥ 1). The average grade for each homework in all the chapters need to be found out.
To solve this, write program which has the main process as Director process, which reads a file containing grades of all homeworks of all chapters and creates x number of Manager processes. Each Manager process will take care of solving a chapter. Each manager process will create y number of Worker process and pass one homework to each of them and they calculate and print the average.
The input file should contain the data according to the value of x and y. For example, the input text file and the process tree for x = 2 and y = 2 will look like the following:

<img width="542" alt="Capture2" src="https://user-images.githubusercontent.com/36938994/66974435-166d3980-f069-11e9-9c18-930fa00e514b.PNG">



In this program we will have to handle diffrenet system call and process. We will create two manager and each manager will manage two workers. Each worker then handle each column of that specific text file conataining student's grade. Since, there are four columns so we will have four workers. Each worker will print out the average for each column. 

###  Linux Terminal
<img width="593" alt="Capture3" src="https://user-images.githubusercontent.com/36938994/66975120-6ea53b00-f06b-11e9-885c-088ba633d3b8.PNG">

The purpose of this project was to understand how simple command interpreter work and how to create different system call to interact with the process. 
