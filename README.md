# Bash-examples1

In essence, Git is a set of command-line utilities that are designed to run in a Unix-style command-line environment. Modern operating systems such as Linux and macOS include built-in Unix command-line terminals. This turns Linux and macOS into complementary operating systems when working with Git. Instead, Microsoft Windows uses the Windows command prompt, a non-Unix terminal environment.

*Git Bash is an application for Microsoft Windows environments that provides an emulation layer for a Git command line experience. Bash is the English acronym for Bourne Again Shell. A shell is a terminal application that is used as an interface with an operating system using written commands. Bash is a popular default shell on Linux and macOS. Git Bash is a package that installs Bash, some common bash and Git utilities on a Windows operating system.*
For this repository I will show some commands seen during the data preprocessing class


## DIRECTORIES

to move between directories we use the **cd+directory** command to move.

## NEW DIRECTORY

To create a new directory we use **mkdir + the name of this**

## CREATE A FILE

To enhance such activity it is common to use the command **nano + file name + extension of this**.

## Show the actual directory

The Bash **pwd** command is used to print the "working directory present". 
The Bash **ls** command is used to "list" the contents of the current working directory.

## Find command

find - search for files in a directory hierarchy.
**find** [-H] [-L] [-P] [-D debugopts] [-Olevel] [path...] [expression]
**find** searches the directory tree rooted at each given file name by evaluating the given expression from left to right, according to the rules of precedence (see section OPERATORS), until the outcome is known (the left hand side is false for _and_ operations, true for _or_), at which point **find** moves on to the next file name.
Some examples:
1. Search for a file that we know the name and extension of:   
find / -name [example.txt]
2. Search for files in a particular location, for example, my user home:  
find /home/kelly -name [example.txt]
3. Perform searches ignoring case:
find /home/kelly-iname [example.txt]
4. To search directories we must use the parameter "type -d", as shown in the example:
find / -type d -name kelly  
5. Search for files by extension:  
find / -type f -name *.sh
## CAT

  cat - concatenate files and print on the standard output.
    **cat** [_OPTION_]... [_FILE_]...
     Concatenate FILE(s) to standard output.
     With no FILE, or when FILE is -, read standard input.

# SCP
**scp** - secure copy (remote file copy program).
**scp** copies files between hosts on a network. It uses **[ssh](https://linux.die.net/man/1/ssh)**(1) for data transfer, and uses the same authentication and provides the same security as **[ssh](https://linux.die.net/man/1/ssh)**(1). Unlike **[rcp](https://linux.die.net/man/1/rcp)**(1), **scp** will ask for passwords or passphrases if they are needed for authentication.
