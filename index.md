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

**`cat` with a path to a directory as an argument**

**`cat` with a path to a file as an argument**
