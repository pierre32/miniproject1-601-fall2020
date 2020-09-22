# GitFlow

  

## What is Git and GiFlow

Git is widely used, open source system which provides performance, security, Flexibility and Distributed Version control to developers worldwide.
Gitflow Workflow is a Git workflow design that was first published and made popular by Vincent Driessen at nvie. The Gitflow Workflow defines a strict branching model designed around the project release. This provides a robust framework for managing larger projects

## What is Version Control System (VCS)?
Version control system is a system that records changes to a file or set of files over time so that you can recall specific versions later by using git command or various git tools available online. Suppose you are a developer and want to keep every version of code or after some particular tasks completion a Version Control System (VCS) is very useful tool. It allows you to revert files back to a previous state, compare changes over time, it allow you to take the other developer code changes using git command, see who modified the files over the time, who has done more number of lines of code, various type of statistics on the repository, who has done the code with bug and when, and many more, basically you can entirely do the tracking of the files over the time and go back to any previous changes.

  

# Git Commands & Terminology

  
### Repository

Repository is a collection of files of various different versions of a project saved in a version control system, e.g., Github.

Usage; Repo on github can be created by creating and account on [github](http://https://github.com/).
<img src="Images/Repo.png" height="300" width="700">
  

### Clone
This commands make a copy of an existing repo on to the local directory. cloning can be done using HTTP or SSH.
    ![Create a repo](https://github.com/mz081130/miniproject1-601-fall2020/blob/master/Images/Clone.png)
    
    git clone <clonePath>

  

### Fork
Forking an official repo allows a developer to save the copy on their personal public repo and no other developers are allowed to push to it, but only the repo owner can pull changes from it
Forking a repo on Github can be done on the upper right corner, simply click **Fork**.
 ![Create a clone](https://github.com/mz081130/miniproject1-601-fall2020/blob/master/Images/Fork.png)

### Branch
Branches are individual projects within a repository. Different branches within a repository can have completely different files and folders, or it could have everything the same except for some lines of code in a file.
Usage: 
Command to find current branch you are in:
    
    git branch	
   
To create a new branch

    git branch <branchname>   
  

### Commit
Git commit is used when we want to save changes to our local files/folder and push the changes to the remote server.
Usage:
 
    git add <branchname>
    git commit -m 'write your comments here'

### Merge
This command combines two branches together. This can be done via github web interface or by using terminal
Usage:

    git checkout master 
    git merge <branchname>
### Checkout

### Push

### Pull

### Remote add/ Remove/ Show

### Status

### Master Branch      
  
Source:[BitBucket](https://www.atlassian.com/git/tutorials/what-is-git),[Medium](https://medium.com/@okandavut/what-is-gitflow-c0be7a659992)
