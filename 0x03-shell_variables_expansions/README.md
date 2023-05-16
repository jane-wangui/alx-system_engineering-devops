0x03. Shell, init files, variables and expansions
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What happens when you type $ ls -l *.txt
Shell Initialization Files
What are the /etc/profile file and the /etc/profile.d directory
What is the ~/.bashrc file
Variables
What is the difference between a local and a global variable
What is a reserved variable
How to create, update and delete shell variables
What are the roles of the following reserved variables: HOME, PATH, PS1
What are special parameters
What is the special parameter $??
Expansions
What is expansion and how to use them
What is the difference between single and double quotes and how to use them properly
How to do command substitution with $() and backticks
Shell Arithmetic
How to perform arithmetic operations with the shell
The alias Command
How to create an alias
How to list aliases
How to temporarily disable an alias
Other help pages
How to execute commands from a file in the current shell

Tasks
0. <o>
Create a script that creates an alias.
Name: ls
Value: rm *
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 0-alias

1. Hello you
Create a script that prints hello user, where user is the current Linux user.
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 1-hello_you

2. The path to success is to take massive, determined action
Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 2-path

3. If the path be beautiful, let us not ask where it leads
Create a script that counts the number of directories in the PATH.
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 3-paths

4. Global variables
Create a script that lists environment variables.
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 4-global_variables

5. Local variables
Create a script that lists all local variables and environment variables, and functions.
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 5-local_variables

6. Local variable
mandatory
Create a script that creates a new local variable.
Name: BEST
Value: School
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 6-create_local_variable

7. Global variable
Create a script that creates a new global variable.
Name: BEST
Value: School
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 7-create_global_variable

8. Every addition to true knowledge is an addition to human power
Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 8-true_knowledge

9. Divide and rule
mandatory
Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.
POWER and DIVIDE are environment variables
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 9-divide_and_rule

10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
mandatory
Write a script that displays the result of BREATH to the power LOVE
BREATH and LOVE are environment variables
The script should display the result, followed by a new line
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 10-love_exponent_breath

11. There are 10 types of people in the world -- Those who understand binary, and those who don't
Write a script that converts a number from base 2 to base 10.
The number in base 2 is stored in the environment variable BINARY
The script should display the number in base 10, followed by a new line
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 11-binary_to_decimal

12. Combination
Create a script that prints all possible combinations of two letters, except oo.
Letters are lower cases, from a to z
One combination per line
The output should be alpha ordered, starting with aa
Do not print oo
Your script file should contain maximum 64 characters
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 12-combinations

13. Floats
Write a script that prints a number with two decimal places, followed by a new line.
The number will be stored in the environment variable NUM.
Repo:
GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 13-print_float
