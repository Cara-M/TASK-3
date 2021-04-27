# Ignoring Files 

It is important to understand how to ignore files in a directory that we do not want to push to GitHib.

 You can ignore:
 - Individual Files
 - Entire Directories 
 - Files inside a directory/anywhere in the repository 
 - All files with the same file extension 

## Ignoring a single file
When pushing files to GitHub, we have the opetion to ignore a single file.

To do this, we use the .gitignore command. 

.gitignore tells Git to ignore the specified files.

If you run a git status after this, the files are still tracked and will still show up. 

You can also open nano and then type the names of the files you want to ignore. 

After running .gitignore, in nano, the files will no longer be tracked.

This means they will no longer show up in git status. 

You will not be able to add them to the staging area. 

## Ignoring an entire directory 
We can also ignore entire directories when pushing changes to GitHub. 

Again, we go to nano to specify what directory to ignore. 
 - You can put a slash after the directory name to specify to ignore
 - directorytoignore/  = ignore this entire directory 
 - **/directorytoignore/  = ignore anything inside this directory 

## Ignoring a single file within a directory 
We have the option to push directories to GitHub, but ignore individual files inside it.

To do this, we can use the following command in nano:
 - **/filetoignore/
This tells Git to ignore the specified file when pushing to GitHUb.

All other files inside the directory will not be affected. 


