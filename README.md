# Simple Shell | UNIX Command Interperter

![The gates of shell](./img/shell.jpeg)

### Introduction
This repository represents a Holberton School project wherein we undertook the task of crafting a command line interpeter similar to the Shell introduced by the renowned Stephen Bourne, using the C programming language. The challenge involved minimizing reliance on standard library functions, opting instead for our custom functions refined over the [<span style="color:#33beff; !important">low level proramming</span>](https://github.com/AhmadYousif89/alx-low_level_programming) course of the past couple of months.

The primary objective of this project was to deepen our understanding of shell functionality. Noteworthy aspects of exploration included comprehending the system environment vatiables, distinguishing between functions and system calls, and mastering the creation of processes using <span style="color:lightgreen;">fork, execve</span> and many other intricacies.

# Getting Started

This project was compiled on Ubuntu 20.04 LTS using the `gcc` compiler with these flags `-Wall -Werror -Wextra -pedantic -std=gnu89`.

In order to use this program, you will need to follow these steps :

- Start by cloning this repository by running this command in your terminal.
```bash
git clone https://github.com/AhmadYousif89/simple_shell
cd simple_shell
```

- Compile the program with these commands.
```bash
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
``` 

- Run the program by executing the compiled file `hsh`.
```bash
simple_shell$ ./hsh
$
```

### STD library custom functions

This list contains some of the custom functions utilized in our project, mirroring the functionality of certain standard C library functions.

| Name | Functionality | 
|------|:---------------|
| _strlen  | Gets the length of string.|
| _strstr  | Find the first occurrence of the substring.|
| _strcmp  | Compare two strings.|
| _strcat  | Append a string to another string.|
| _strcpy  | Copy string from src to dest.|
| _strchr  | Locates a character and return a string from its position.|
| _strdup  | Duplicate a string in memory.|
| _strtok  | Splits a string into words.|
| _memcpy  | Copy number of byte from src to some memory area.|
| _memset  | Fill a string with some characters.|
| _putchar | Print to stdout using low level system call (write).|

### List of functions and system calls

This list contains the already builtin functions and system calls we were allowed to use and utilize in our project.

| Name | Functionality |
|------|:---------------|
| chdir | Changes the current working directory. [`man chdir`](https://linux.die.net/man/3/chdir)|
| close | Closes the file discriptors. [`man close`](https://linux.die.net/man/3/close)|
| execve | Replaces the currently running process with a new process. [`man execve`](https://linux.die.net/man/3/execve)|
| exit | Terminates the process and return the exit code status. [`man exit`](https://linux.die.net/man/3/exit)|
| fork | Creates a new process by duplicating the calling process.[`man fork`](https://linux.die.net/man/3/fork)|
| free | Free allocated memory on demand. [`man free`](https://linux.die.net/man/3/free)|
| getcwd | Gets current working directory. [`man getcwd`](https://linux.die.net/man/3/getcwd)|
| getline | Reads an entire line from a stream. [`man getline`](https://linux.die.net/man/3/getline)|
| getpid | Returns the process ID (PID) of the calling process. [`man getpid`](https://linux.die.net/man/3/getpid)|
| isatty | Tests whether a file descriptor refers to a terminal or not. [`man isatty`](https://linux.die.net/man/3/isatty)|
| malloc | Allocates dynamic memory. [`man malloc`](https://linux.die.net/man/3/malloc)|
| open | Opens a file to process. [`man open`](https://linux.die.net/man/3/open)|
| signal | Used to handle the Ctrl+C termination signal. [`man signal`](https://linux.die.net/man/3/signal)|
| stat | Display file or file system status. [`man stat`](https://linux.die.net/man/3/stat)|
| wait | Suspends execution of the calling thread until one of its children terminates. [`man wait`](https://linux.die.net/man/3/wait)|
| write | Used to print to stdout, stderr. [`man write`](https://linux.die.net/man/3/write)|

#### Author

[Ahmad Yousif](https://github.com/AhmadYousif89)

**Happy Coding 👋**
 
 
 
 
 
 
 
 
 
 
 
 
 