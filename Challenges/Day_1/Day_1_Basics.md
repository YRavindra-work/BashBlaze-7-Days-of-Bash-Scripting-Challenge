Welcome to Day 1 of the Bash Scripting Challenge! Today, we will cover the basics of bash scripting to get you started. Let's dive in:

## Task 1: Comments

In bash scripts, comments are used to add explanatory notes or disable certain lines of code. Your task is to create a bash script with comments explaining what the script does.

Solution: 

#!/bin/bash

#This is a single-line comment.

#This is a multi-line comment.
#This is a multi-line comment.

## Task 2: Echo

The `echo` command is used to display messages on the terminal. Your task is to create a bash script that uses `echo` to print a message of your choice.

Solution:

#!/bin/bash

echo “Hey There, this is task2 solution using echo cmd”

## Task 3: Variables

Variables in bash are used to store data and can be referenced by their name. Your task is to create a bash script that declares variables and assigns values to them.

Solution:

#!/bin/bash

# This script defines two variables.

Variable_1=” First Variable ”
Variable_2=” Second Variable ”

## Task 4: Using Variables

Now that you have declared variables, let's use them to perform a simple task. Create a bash script that takes two variables (numbers) as input and prints their sum using those variables.




Solution:


#!/bin/bash

read value1

read value2

sum=$(($value1 + $value2))

echo “Sum of two values is: $sum”




## Task 5: Using Built-in Variables

Bash provides several built-in variables that hold useful information. Your task is to create a bash script that utilizes at least three different built-in variables to display relevant information.

Solution:

#!/bin/bash

# This script displays the common build-in variables like Current Directory and Current Date

echo "The current directory is: \"$PWD\""
echo "The current date is: \"$(date)\""



## Task 6: Wildcards

Wildcards are special characters used to perform pattern matching when working with files. Your task is to create a bash script that utilizes wildcards to list all the files with a specific extension in a directory.

Solution:

#!/bin/bash

# This Script displays the list of files using wild card

listfiles = $(ls *)
echo “The list of all files in the current directory are: $listfiles”


## Submission Instructions:

Create a single bash script that completes all the Tasks mentioned above. Add comments at appropriate places to explain what each part of the script does. Ensure that your script is well-documented and easy to understand.

To submit your entry, create a GitHub repository and commit your script to it.

Good luck with Day 1 of the Bash Scripting Challenge! Tomorrow, the difficulty will increase as we move on to more advanced concepts. Happy scripting!
