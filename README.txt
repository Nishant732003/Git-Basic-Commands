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
 


5.'Repository area
This area actually contains the details of all your previous registerd version
and the files in this area git alreday manges them and know their version history.

 6.How to move workign area file to staging area?
 git add filename
 7.to remove from stagig area using cached so git do not cached the file
 "git rm --cached <file>...

 8.Now you want tomove file from staging area to repository area

 9.'commit' is a particular version of the project. 
  It captures the  project 's staged changes and craete version of it.
   'giut commit'to resister staging area changes to repo
10.
'git log'
list down all th e commits of the repository.If you want to exit out of git log prompt press'q'.

11.'git restore <file>' it will delete all the things that are in staging area but yet noot commited
If we did some dirty piece of code and now no more want it .Instaed of deleting every change line by line
we can restore it.

give last commited version of file
12.'git restore --staged <file>'-> It removes file from  chnages from staging area to the working area .It will
keep chnages in working area
This oinly works if changes are in staging area
