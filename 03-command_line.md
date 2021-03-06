# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

* pwd - print working directory

* ls list files (-a all contents, -l long format, -t order by most recently modified)

* cd change directory

* mkdir make directory

* touch make file

* cp copy

* mv move files or rename

* rm remove file -r recursive, removes directory

* cat - outputs file content to terminal

* '>' redirect output or overwrite

* '>>' - appends

* '|' pipe command to command redirect





---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  list directory contents
`ls -a`   list all including hidden
`ls -l`   longform
`ls -lh`  longform and print sizes in human readable format
`ls -lah`  list all, longform , and sizes in readable format
`ls -t`  list contents and sort by date modified
`ls -Glp` list color coded(?) longform, display directories with /



---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

* 'ls -1'	Displays each entry on a line.
* 'ls -t'	Displays newest files first
* 'ls -m'	Displays the names as a comma-separated list.
* 


---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

xargs allows commands to accept standard input as arguments. 

a common use would be with the find command to then perform another command on the results. for example:

'find ... | xargs rm'

removes whatever files that were found

 

