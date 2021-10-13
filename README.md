This will provide information about git.

##Configure git bash
--Setting your Git #username (Actual username) for every repository on your computer
	Open Git Bash.
	Set a Git username:
	$ git config --global user.name "#username"
	
	Confirm that you have set the Git username correctly:
	$ git config --global user.name
	> #username
	
	$ git config --global user.email "mail@example.com"
	$ git config --global user.email
	> mail@example.com

##creating new project
create a repository in github
$ git checkout "https url to created repository"
$ git init

##commiting first file
create any file in checkout repository
check git status - it will show untracked files
commit the file using git commit -m "relavent commit message"
push the file to remote repository using git push





