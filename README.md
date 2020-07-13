# Linux_quize_questions
Contains questions and their solutions with required explanation

#### Q1 Name of method in shell to take input from user
  - read
  
#### Q2 `test date` what will be the output of this command
  - no output
    - test command: The test command is used to check file types and compare values. Test is used in 		            conditional execution
    - {syntax : test condition; test condition && true-command; test condition || false command; test condition && true-command || false_command}
    - It is used for:
       - File attributes comparisons
       - Perform string comparisons
       - Basic arithmetic comparisons
      
#### Q3 How to run a shell script in a debug mode
  - `bash --debug a.sh`
  - debug mode: debug mode is a user interface implemented in a computer program that allows the user to view and/or manipulate the program's internal state for the purpose of debugging.

#### Q4 How to run multiple command in shell
  - `cmd1; cmd2` run both 1 and 2 regardless of success or failure {correct solution}
  - `cmd1 && cmd2` run 2 if 1 succeeded
  - `cmd1 && cmd2` run 2 if 1 succeeded

#### Q5 #! called
  - she bang and hash bang both

#### Q6 What is the exit code of a script got executed successfully
  - 0
  -  to check exit code run echo $? after running the comman {$? variable is set to the return code of the last executed command}
  - exit code: Exit codes are a number between 0 and 255, which is returned by any Unix command when it returns control to its parent process. Other numbers can be used, but these are treated modulo 256, so exit -10 is equivalent to exit 246, and exit 257 is equivalent to exit 1.

#### Q7 How to run script so that input and output both will print
  - `bash -x script_name`

#### Q8 How to list only hidden files and folders in linux
  - `ls -a | grep '^\.'`

#### Q9 Jack user can make a directory outside Jack user in:
  - `/var/tmp/`  and  `/tmp/`
