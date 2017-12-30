# practice
#**Project Name:**
##Note for GIT

##Description:
##Table of Contents:
##Installation:
##Usage:
##Contributing:
##Credits:
##License:


getting familiar with the git process
why git is good
-- keeps track of changes to code.
-- Synchronizes code between different people.
-- Test changes to code without losing the original.
-- Revert back to old versions of code.

Three states of the git
	- committed means that the data is safely stored in your local database
	- Modified means that you have changed file but have not committed it to you  	
		database yet
	-Staged means that you have marked a modified file in its current version to go into 		your next commit snapshot.


FREE CodeCamp
https://www.youtube.com/watch?v=2GO1a1vgNrc&list=PLWKjhJtqVAbkFiqHnNaxpOPhh9tSWMXIF&index=2

Github Workflow

1. Branching	- don’t make changes to master branch. So make a new branch
2. Commits	- make a few change then make Commits, as many a you like
3. Pull Request	- compare to the master branch
4. Collaborate	- review a code with others
5. Merge	- code approved the combine to the master branch

— Fork is “copy” to your own account remote
- Clone  is making a copy local


Commit ID are IMPORTANT
ID are 40 character SHA-1 hash
they include “blobs” and metadata
blob= reduce version of code
metadata= who and what time

—Why 2 step commit
example you are working on 2 files
one of them are substantial so you create a git add to the file
this will move into the staging area, when git commit is executed
then only the files in staging will be saved into history

#git command
##below are some key command prompt to remember

* git clone --- url of  a repository, store on computer, creates fork on line*
* git add --- after clone, add to staging area
* git diff --- shows what change
* git commit --- saves a change to repository, keep old version
      * commit -am adds a a message
* git status ---- what is happing in the repository
* git push origin master --- sends the updated online
* git pull --- retrieves changes for online
* git log ---- history of the repository
* git reset --- roll back to a previous file,
    * git reset --hard <commit ie 4761626>  (code back to a previous commit)
    * get reset --hard origin
