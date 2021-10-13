# Shell-in-C
Preparation

For this assignment you will need to be able to log in to the linux server at cs.csis.work.  You will want to be familiar with using ftp to upload files
to your account (the lab machines have WinSCP but any ftp software will work), using ssh for remotely logging into a shell under your account name (I'm not
sure what the lab machines have.  I have used Putty successfully, in the past), and you will also want to be familiar with the basic use of terminal commands
in Linux.  (https://maker.pro/linux/tutorial/basic-linux-commands-for-beginners (Links to an external site.))

Assignment
Write a C program that acts as a shell (or command interpreter).  This program should be able to take command lines from the user and execute them.  This includes 
command arguments and file redirection.  Below is a list of instructions your shell should be able to correctly handle.  They are ordered roughly from least to most
complicated to handle, so as you evolve your shell I recommend you deal with each in turn from top to bottom. 

ls
cat myfile
ls -l
ls -al
gcc -o myprog prog.c
cat myfile > otherfile
