# laB
- create a new Git repository:

cd "C:\Local_Git_Repository"		//"C:\your location"


- create a new directory :

mkdir <name of new directory for new Git repository>		//eg: mkdir lab1


- changing to the directory of the new repository:

git init		//used to initialize a new Git repository
			//only needs to be run once per repository when you are creating a repository
			//running "git init" again will overwrite your existing repository


- adding snapshots of the files to the staging area, preparing them for the “Commit” action:

git add HelloWorld.py		//git add (your file)
				//note: does not commit the file to the Git repository


- to verify that the file has been added:

git status		//show the changes to commit


- commit file to git repository:

git commit -m "Initial version to display text message on console"		//git commit -m"your comment"


- view all branches:

git branch				//used to make update easier


- create branch:

git branch <new branch name>		//eg: git branch "bug-fix1"


- how to checkout/exit branch:

git checkout <branch name>		//git checkout "bug-fix1"

- To merge a branch into the current branch:

git merge <branch to be merged>		//eg: git merge "bug-fix1"

- Commit and push the new Readme.md file to GitHub:

git add Readme.md			//add > commit > push
git commit -m "add submodules"
git push Readme.md


- create git submodules:

git submodule add <Git submodule repository URL>	//eg: git submodule add https://github.com/JohnProject.git


- clone submodules:

git clone <URL of repository to clone>			//eg: git clone https://github.com/Jeff-sp22/lab1

- push an existing repository from the command line:

git remote add origin https://github.com/Thaqif03/laB.git
git branch -M main
git push -u origin main
