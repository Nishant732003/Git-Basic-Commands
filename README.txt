1. 'git init'

 powers your folder to manage by folder and intilaizes new wmpty repo
it also create .git folder 
it has all relevant logic to maintin your folder

2. rm-rf .git  //for linux
to dlete .git folder

3. 'working area'
bunch of files that are not handled by git it means that changes done or 
to be done in the files are not mange dby git yet.
a file which is in working area is considered not in staging area 

when we do git status and we see bunch of untracked files then wecan see this  to be in 
working area

4.Staging area 
it is going to tell you what are the other files that are going to part of next version.
This staging area is the place where git knows what changes are to be done fron last version to 
next version
 How to move workign area file to staging area?
 git add filename
