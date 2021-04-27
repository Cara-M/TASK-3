<<<<<<< HEAD
<<<<<<< HEAD
<h6>Licensing<h6>
Any work that is produced in the Uk, the owner has copyright to that file created.
There are two types of licensing: Permissive and Strong Copyleft

The permissive licensing allows the public to use, modify, and share the base repository/code. Also, no conditions for the downstream license.
Common permessive license seen:
- MIT
- Apache 2.0
- ISC
- BSD

Note MIT allows a project to be used as a dependency in another.

The strong copyleft licensing requires the user wanting to use the owner's repository/code must have the same licensing as the owners.
Common strong copyleft license seen:
- GPL v2, v3
- AGPL v3

<strong>Steps to view licensing</strong>

- Need to clone the repository you want.
git clone [URL]

- Then after you clone the repository list all files.
ls

- Look for the right directory possesing the licensing file.
cd [directory]

- Once found the licensing file, open the file to check what kind of licensing it is.
cat LICENSE
=======
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


>>>>>>> feat-cara
=======
# Feature Branch Model (FBM)

The core idea behind the **Feature Branch Model** is that all feature development should take place in a dedicated branch instead
of the *main* branch. This makes it easy for multiple developers to work on a particular feature without messing with the
main codebase. It also means that the *main* branch will never contain broken or untested code, which facilitates a continous 
integration environments.

## How it works

The FBM works off of a central repository where *main* represents the official project history. Instead of commiting directly on the 
local *main*, developers create a new branch every time they stat work on a new feature. Feature branches should have descriprive names.
We do this to give a clear, highly-focused purpose to each branch. 

## Example

git branch new-branch --- This will create a new branch

git checkout new-branch --- This will move you into the specified branch

git checkout -b new-feature --- this will create a branch as well as move you into it
>>>>>>> feat-matt
