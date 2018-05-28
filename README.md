# Terminal Cheatsheet

#### Purpose

This is cheatsheet is for the benefit of myself and others. It will list and define the use cases of both simple and advanced terminal commands.

#### Appendix

[Navigation](#navigation)<br/>
[Reading and Writing Files](#reading-and-writing-files)<br/>
[System](#system)<br/>

### The Cheatsheet

---

### NAVIGATION

| Command        | Description   | 
| ------------- | ------------- | 
| `cd` | Change directory. |
| `cd ../`| Move up one directory. |
| `ls` | Show all files and folders within the current directory |
| `ls -A` | Show all files and folders within the current directory, including hidden folders & files |
| `pwd` | Shows the current absolute path |
| `which <program_name>` | Shows the absolute path of the given program name |

### READING AND WRITING FILES

| Command        | Description   | 
| ------------- | ------------- | 
| `pwd` | Show the current absolute path |
| `echo <string>`| outputs the string passed as an argument |
| `echo <string> >> <file_name>`| appends the string passed as an argument into the given file. If the file doesn't exists, it is created. |
| `cat <file_name>` | Read the contents of the given file name within the terminal |

### SYSTEM

| Command        | Description   | 
| ------------- | ------------- | 
| `history"` | Lists the the most recent terminal commands in descending order. |
| `printenv` | Lists all environmental variables.  |


<!-- | Command        | Description   | 
| ------------- | ------------- | 
| `history"` | Lists the the most recent terminal commands in descending order. |
| `printenv` | Lists all environmental variables.  |
|  -->