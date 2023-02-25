# **List of most useful commands in  Ubuntu**

Here is a list of some most useful commands for ubuntu

## **Summary**
| Command        | Description          | 
| :-------------: |:-------------| 
| < >       | Replace inside accordingly without single/double quotes | 
| `pwd`      | To Print Working Directory | 
|  `ls`      |  To list the content of current folder     |  
|  `ls -l`      |  To list the content of current folder in long list format     | 
|`ls -a`    | to list **all** the contents of a folder including the hidden files|
| `cd <folder_name>`; | change directory to a given folder_name|
| `cd ..`   | Go back a folder level |
| `cd ../..`   | Go back two folder level |
| `more <filename>`     | To see what's in a file|
| `man <command_name>`      | To get the manual of a command      |
| `clear` | To clear the terminal      |
| `echo <hello_world>`      | To print anything to the terminal      |
| `echo text >> filename`|To Print the text to a file  |
|  ` tree`  |  To see all the files and folders inside the current directory in an actual tree format  |
|  ` find `  |  To see all the files and folders inside the current directory and in their subdirectories|
|  ` find <folder name>`  |   To display the tree of a  folder  |
|  `find -name <filename/foldername>` |To search a file or a folder by it's name|
| `mkdir <folder_name>`      | make new directory/folder  |
| `touch <filename>`       | To create a new file      |
| `<command_name> --help`      | To find more details about the command |
| `cp <file_name> <new_path>`| To copy a file to another path      |
| `cp -r <folder_to_copy> <name_of_copy>`| To copy a folder with all of it's files to another path |
| `rm <filename>`      | To remove a file       |
| `mv <file_name/folder_name> <new_filename/folder_name>` | To  **rename**  a file/folder to new file/folder name|
| `mv <filename> <new_path>` | To  **move**  a file to new path  |
| `rmdir <directory_name>`  | To remove an empty folder , only empty folder will be removed  |
| `rm -r <directory_name>`   | To remove a folder ( even if it's not empty ) and it's content recursively           |
| `exit`      | To exit the terminal      |
  
## **Command Description**
## ***Navigation*** 
## *Print Working Directory*

 Type `pwd` into the terminal and press enter to see the path of the folder. `pwd` stands for "print working directory".
## *List*
 Type `ls` into the terminal to see what's in the current folder. `ls` stands for "list".The folders will show in blue color and files will have their extension.

## *Long List Format*
Add a **flag** to a command to use it different ways like this: `ls <flag>`. List the contents of the `folder_name` folder in "long list format". To do that add the `-l` flag to the "list" command.
## *List All*
Use `ls -a` to list **all** the contents of a folder including the hidden files.
## *Change Directory*
Use `cd <folder_name>` to go into a folder. `cd` stands for "change directory".


Use `cd ..` to go back a folder level. The two dots will take you back one level. 

Use `cd ../..` to go back two folders. Each set of dots represents another folder level.
## *More*
To see what's in a file use `more <filename>`. 
## *Clear*
Empty the terminal with `clear`.
## *Echo*
Use `echo` command to print anything to the terminal. 
## E*cho to File*
Print to a file instead of the terminal with `echo text >> filename`. 
## *Find*
Use `find` to find things or view a file tree. Use command ` find <folder name`  to see all the files and folders withing it.
## *Find Subfolder*
Use `find <folder_name>` to display the tree of a  folder. 
## *Find with name*
Use `find -name <filename/foldername>` to search a file or a folder by it's name.

# ***Creation & Deletion***
## *Make Directory*
Make a new folder with `mkdir <folder_name>`. `mkdir` stands for "make directory". 
## *Touch*
Use `touch <filename>` to create a new file. 
## *Help*
Most commands have a `--help` flag to show what the command can do. Here's an example: `command <flag>`.
## *Copy*
`cp` stands for "copy". 
Use `cp <file_name> <new_path>` to copy a file to another path.
## *Copy recursively*
Use `cp -r <folder_to_copy> <name_of_copy>`to copy a folder and **all its content** to another location.
## *Remove*
USe `rm <filename>` to remove a file. 
## *Rename*
Rename a file with `mv` command: `mv <filename> <new_filename>`. `mv` stands for "move", it can **rename or move** something. 
## *Move*
`mv` can also be used to move files to another location/folder. Use command : `mv <file> <destination>`.
## *Remove Directory*
Use `rmdir <directory_name>` to remove an empty folder. `rmdir` stands for "remove directory". this command will remove a directory/folder if and only **if the directory/folder is empty**.
## *Remove Recursively*
There's a `-r` flag that says, `remove directories and their contents recursively`. That will remove the folder and everything in it. So use command `rm -r <directory_name>` to **remove a folder even if it's not empty**.
## *Exit*
Use the "exit" command to exit the terminal.

### Credits
* [freecodecamp.org](https://www.freecodecamp.org/)
