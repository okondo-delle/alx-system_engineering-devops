
# 0x02. Shell, I/O Redirections and filters
## LEARNING OBJECTIVES
* What do the commands head, tail, find, wc, sort, uniq, grep, tr do
* How to redirect standard output to a file
* How to get standard input from a file instead of the keyboar
* How to send the output from one program to the input of another program
* How to combine commands and filters with redirections
--
## TASKS

### task one
Write a script that prints “Hello, World”, followed by a new line to the standard output.
```
julien@ubuntu:/tmp/h$ ./0-hello_world 
Hello, World
julien@ubuntu:/tmp/h$ ./0-hello_world | cat -e
Hello, World$
julien@ubuntu:/tmp/h$ 
```
