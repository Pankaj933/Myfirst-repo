## What is git
Git is a free open source Git is a popular version control system. It was created by Linus Torvalds in 2005, and has been maintained by Junio Hamano since then. it is used to manage source code in software development.

It is used for:

Tracking code changes
Tracking who made changes
Coding collaboration

## What does git do?
1. Storage source code and its development history.
2. tracking changes to source code.
3. Manage projects with Repositories
4. Clone a project to work on a local copy
5. Control and track changes with Staging and Committing
6. Branch and Merge to allow for work on different parts and versions of a project
7. Pull the latest version of the project to a local copy
8. Push local updates to the main project

# Working with git
* Initialize  Git on a folder, making it a Repository
* Git now creates a hidden folder to keep track of changes in that folder
* When a file is changed, added or deleted, it is considered modified
* You select the modified files you want to Stage
* The Staged files are Committed, which prompts Git to store a permanent snapshot of the files
* Git allows you to see the full history of every commit.
* You can revert back to any previous commit.
* Git does not store a separate copy of every file in every commit, but keeps track of changes
made in each commit!

## what is github?
** Github is a web-based platform for hosting and managing Git repositories. 
* It provides tools for collaboration, version control, and project management, making 
* it easier for developers to work together on code from anywhere.
* GitHub integrates with Git to provide a sameless workflow for both individual and teams. 
* Git is not the same as Github.
* GitHub makes tools that use Git.
* GitHub is the largest host of source code in the world, and has been owned by Microsoft since 2018.
* In this tutorial, we will focus on using Git with GitHub.

# what is GitHub

* GitHub is a code hosting platform for collaboration and version control.
* GitHub lets you (and others) work together on projects.

# ** GitHub essentials are: **
* Repositories
* Branches
* Commits
* Pull Requests
* Git (the version control software GitHub is built on)
* Example
* $ git push origin heroku
* $ cd /etc/
* $ ls

1. * Repositories
* A GitHub repository can be used to store a development project.
* It can contain folders and any type of files (HTML, CSS, JavaScript, Documents, Data, Images).
* A GitHub repository should also include a licence file and a README file about the project.
* A GitHub repository can also be used to store ideas, or any resources that you want to share.

2. * Branches
* A GitHub branch is used to work with different versions of a repository at the same time.
* By default a repository has a master branch (a production branch).
* Any other branch is a copy of the master branch (as it was at a point in time).
* New Branches are for bug fixes and feature work separate from the master branch. When changes are ready, they can be merged into the master branch. If you make changes to the master branch while working on a new branch, these updates can be pulled in.

3. * Commits
* At GitHub, changes are called commits.
* Each commit (change) has a description explaining why a change was made.

4. * Pull Requests
* Pull Requests are the heart of GitHub collaboration.
* With a pull request you are proposing that your changes should be merged (pulled in) with the master.
* Pull requests show content differences, changes, additions, and subtractions in colors (green and red).
* As soon as you have a commit, you can open a pull request and start a discussion, even before the code is finished.
* A a great way to learn GitHub, before working on larger projects, is to open pull requests in your own repository and merge them yourself.
* You merge any changes into the master by clicking a "Merge pull request" button.

5. * Git (the version control software GitHub is built on)

# Git Repository management

* Clone a repository with git clone <repository-url> 
* Example command: git clone 
https://github.com/username/repository.git

* Us egit stataus to view changes, staged, and untracked files.
* List Git configuration with git config List* 

Types of git status
1. untracked
* file is new and not added to Git yet.
* use git add track it.

2. Modified 
* Flie has been changes but not yet staged.
* Use git add to move it to the staging area 

3. Stages
* File is ready to be committed.
* Use git commit to save changes

4. Unmodified
* No changes since the last commit.
* File is uo-to date window repository. 

PS C:\Users\Lenovo\Desktop\git and github> git -v
git version 2.47.1.windows.2
PS C:\Users\Lenovo\Desktop\git and github> git clone https://github.com/72SAIFUDDIN/myfirstprojrct.git
Cloning into 'myfirstprojrct'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.
PS C:\Users\Lenovo\Desktop\git and github> git status
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\Lenovo\Desktop\git and github> cd myfirstproject
cd : Cannot find path 'C:\Users\Lenovo\Desktop\git and github\myfirstproject' because it does not exist.
At line:1 char:1
+ cd myfirstproject
+ ~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\Lenovo...\myfirstproject:String) [Set-Location], ItemNotFoundException     
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\Lenovo\Desktop\git and github> cd .\myfirstprojrct\
PS C:\Users\Lenovo\Desktop\git and github\myfirstprojrct> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\Lenovo\Desktop\git and github\myfirstprojrct> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")













