A repository for the Introduction to Operating System course, in Amirkabir University of Technology Under supervision of Dr. Hossein Nourikhah. 

An operating system acts as an intermediary between the user of a computer and computer hardware. The purpose of an operating system is to provide an environment in which a user can execute programs in a convenient and efficient manner.
An operating system is a software that manages the computer hardware. The hardware must provide appropriate mechanisms to ensure the correct operation of the computer system and to prevent user programs from interfering with the proper operation of the system.

This project consists of designing a C program to serve as a shell interface
that accepts user commands and then executes each command in a separate
process. This project can be completed on any Linux, UNIX, or Mac OS X system.
A shell interface gives the user a prompt, after which the next command
is entered. The example below illustrates the prompt osh> and the user’s
next command: cat prog.c. (This command displays the file prog.c on the
terminal using the UNIX cat command.)
osh> cat prog.c
This project is organized into two parts: (1) creating the child process and
executing the command in the child, and (2) modifying the shell to allow a
history feature.

1. When the user enters !!, the most recent command in the history is
executed.
2. When the user enters a single ! followed by an integer N, the Nth
command in the history is executed
