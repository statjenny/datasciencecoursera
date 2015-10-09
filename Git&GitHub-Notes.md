#GIT & GitHub Notes

##1. Git(Local Repositories)
###(1)Setup Git
	$ git config --global user.name 'Jenny Liu'  [set user name]
	$ git config --global user.email 'ann.qian@hotmail.com'  [set user email]
	$ git config --list		[Confirm your configure]
	
###(2)Common Command
- pwd		[Print the working directory]
- clear		[Clear the screen]

- ls		[List all the files & folders in the current directory]

	
	$ls-a	[List hidden & unhidden files and folders
	
	$ls-al	[List details for the hidden and unhidden files and folders]

- cd		[Change Directory]

	-cd..	[Change directory to one level above your current directory]
	
- mkdir	    [make direcotry]
- touch		[Create an empty file]
- cp		

	$cp file directory		[copy a file to a specific directory]
	
	$cp -r directory1 directory2		[copy contents of directory1 to directory2]

- rm		

	$rm file		[delete a file]	
	
	$rm -r directory	[delete a directoory]
	
- mv		

	$mv file directory		[move a file to a specific directory]
	
	$mv file newname_file	[rename file to newname]

- date		[Print today's date]
- echo		[Print whatever arguments you provide]
- exit		[Close]

##2. GitHub(Remote Repositories)

###(1) Creating a local copy
- Initialize a local Git Repo	[$git init]
- Point a local repo to remote repo	[$git remote add origin (url)]

### (2) Make a local copy
- git clone (url)

### (3) Check Git Status
- git status

### (4) Check Git Log
- git log

##3. GitHub Repo
### Add
- git add (files)
- git add . 	[Add untracked files]
- git add -u [Updates tracking for files that changed names or were deleted]
- git add -A [Add Files & TRACK]
### Commit
- git commit -m 'message'		[updates ur local repo]
### Point local to Remote
- git remote add origin master (url)
### Push
- git push 
- git push -u origin master
###(4) Branch
- git checkout -b branchname		[Create a branch]
- git branch			[See what branch you are on type]
- git checkout master	[switch back to the master branch type]
### (5) Pull
- git pull origin master



