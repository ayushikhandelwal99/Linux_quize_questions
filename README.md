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

#### Q10 Oracle linux fall in which distribution category
  - RPM
  
#### Q11 Name of installer of OS in any linux distribution
  - Anaconda
  
#### Q12 RHEL stand for
  - Redhat Enterprise Linux
  
#### Q13 Original founder of linux kernal
  - Linus Torvalds
  
#### Q14 Linux kernal designed in which language
  - C
  
#### Q15  Kernal name of Man OS
  - Darwin
  
#### Q16 Unix family OS written in which language
  - C & assembly
  
#### Q17 Type of linux kernal is
  - Monolithic
  
#### Q18 user files still left on the system even if you delete the user?
  - True
  
#### Q19  Default desktop environments for fedora are
  - GNOME
  
#### Q20 Linux was developed as
  - clone of UNIX
  
#### Q21 Name the software that lets you run multiple OS on one server
  - Hypervisor
  
#### Q22 Chrome OS is based on which linux distribution?
  - BOSS (Bharat Operating System Solutions)
  
#### Q23 Does anaconda installer supports File Transfer Protocol?
  - True
  
#### Q24 What command gives one-line infornmation about a particular command?
  - `whatis`
  
  - apropose command:  apropos is a command to search the man page files in Unix and Unix-like operating systems. It is particularly useful when searching for commands without knowing their exact names.
    - {Syntax: ` apropos [OPTION..] KEYWORD...` }
  
#### Q25 One mode of operation in which a program can run
  - user mode
  
#### Q26 Which package manager cannot install package dependencies on its own?
  - rpm
  
#### Q27 simplest way to deny someone to access their account is?
  - changing shell to `/sbin/nologin`
  
#### Q28  What makes up a linux kernal?
  - Base Kernal and Kernal Modules

#### Q29  To repeat the last command in bash shell history
  - `!!`
  
#### Q30 To start another shell under the current shell you use the command:
  - bash,sh,csh
  
#### Q31 With which userspace is linux typically paired?
  - GNU
  
  - GNU: GNU's Not UNIX
  - UNIX: Uniplexed Information and Computing Service
  - MINIX: `mini-Unix` Unix-like operating system based on a microkernel architecture.
  - BSD: Berkeley Software Distribution: operating system based on Research Unix
  
#### Q32 can a normal user execute commands present in `/sbin` directory?
  - No in 99% cases
  
#### Q33 Which tool is similar to "find" except that it uses an index to search?
  - `locate`
  
#### Q34  Typind "cd" command at shell prompt will take you to which directory?
  - $HOME
  
#### Q35 Name of directory where every user can read and write
  - `/tmp`
  
#### Q36 How to add user in linux
  - `adduser <username>`  or `useradd <username>`
