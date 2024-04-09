# Lab Report 1

## `cd`
**`cd` no arguments**

![Image](cd1.png)

Absolute Path: /workspaces/cse15l-lab-reports

I got this output because `cd` with no argument results in being taken to the home directory.
 
This is not an error.


**`cd` with a path to a directory as an argument**

![Image](cd2.png)

Absolute Path: /workspaces/cse15l-lab-reports

I got this output because I changed the directory into text.

This is not an error.

**`cd` with a path to a file as an argument**

![Image](cd3.png)

Absolute Path: /workspaces/cse15l-lab-reports/text


I got this output because you cannot `cd` into a file. A file is not a directory, so you cannot use `cd` on it.

The output is an error because you cannot change directories into a file. hello.txt is not a directory, so the input resulted in an error.
  

## `ls`
**`ls` no arguments**

![Image](ls1.png)

Absolute Path: /workspaces/cse15l-lab-reports

I got this output because `ls` lists all the files in the current directory.

This is not an error.

**`ls` with a path to a directory as an argument**

![Image](ls_2.PNG)

Absolute Path: /workspaces/cse15l-lab-reports

I got this output because I `ls` to text, a directory, and then it listed the files within this directory (hello.txt)

This is not an error.


**`ls` with a path to a file as an argument**

![Image](ls3.png)

Absolute Path: /workspaces/cse15l-lab-reports

Since `ls` lists files, I got "cat.md" as my output since `ls` simply repeats the file name if used on a file.

This is not an error since `ls` can be used on a file, but it will just repeat the input as there are no more files to be listed.


## `cat`
**`cat` no arguments**

![Image](cat1.png)

Absolute Path: /workspaces/cse15l-lab-reports

I got this output because typing `cat` without an argument makes it read from standard input. This means that it is waiting for an input by the user, as shown by the blank.

This is not an error since the terminal is waiting for user input, and is not blank by error.


**`cat` with a path to a directory as an argument**

![Image](cat2.png)

Absolute Path: /workspaces/cse15l-lab-reports

I got this output because `cat` is supposed to display the content of files, not directories. 

This is an error because `cat` is supposed to be used on files in order to see the content of them. So, trying to use `cat` on a directory results in an error.



**`cat` with a path to a file as an argument**

![Image](cat2.png)

Absolute Path: /workspaces/cse15l-lab-reports

I got this output because `cat` displays the contents of files, and, in this case, the file is cat.md.

This is not an error.


