

# Git
## What is Git?
### Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
#### Download Git:
1. Install as a package
2. Install via another installer
3. Download and compile the source code
#### We use git commands in terminal window to chick our GitHub file and we can write many command in this window when inside GitHub file like:

##### To determine the state of files, utilize the git status command:

$ git status

##### Track one file only by using the following format:

git add filename

##### After staging one or multiple files, we should commit the changes and record what we did within the commit message:

$ git commit -m “made change x,y,z”

*This step has committed changes for the file or files (you can have one commit message for multiple files, if applicable) to the HEAD

##### Next, we would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.

##### Example:(your file's name is master)

$ git push origin master

This command pushes changes from the local “master” branch to the remote repository named “origin”.

*For cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local repository. However, these names can be changed by the user.
