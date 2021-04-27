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
