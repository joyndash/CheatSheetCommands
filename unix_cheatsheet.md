# Joy's unix cheatsheet
## Displaying a directory
### ls
Lists the names of files in a particular unix directory
### ls –lh
Show long listing of files
### ls -a
Show hidden files as well
### ls -latr
List in reverse time order
### ls -l *.sh 
List all files with .sh extension
### ls dir
Lists file inside directory.

## Deleting files
### rm file
Deletes file
### rmdir dir
Removes empty directory dir
### rm -r dir
Removes directory dir and all of its contents

### mkdir dir
Creates empty directory called dir

## Change directory
### cd dir
Changes directory to dir
### cd .. 
Changes working directory to parent
### cd 
Changes working directory to home

## Copying files
### cp
Make copies of your files.
### cp file file2 
Copy file into file2
### cp file dir 
Makes a copy of file file inside directory dir
### cp -r dir dir1 
Copies a directory dir & contents to another directory dir1

## Renaming files
### mv file file2 
Renames the file file as file2
### mv file dir 
Moves the file inside directory dir

### man
Displays the manual page for command.Give usage information for any UNIX command.Press space bar or enter to page through man page.Type q to quit.
### pwd 
Shows the present working directory.

## Viewing and editing files
### cat file 
Show entire content of filename
### cat file1 > file2 
Copy one file into a new file
### cat file1 >> file2 
Append one file into another
### more file 
Incrementally display content of filename
### less file
Similar to more, but with additional features
### head file
Display the header
### tail file 
Display the footer
### file file 
Show file type
### emacs 
Extensible and customizable text editor
### nano 
Simple text editor