# Git-GitHub-Actions-Linux

### Here you will learn some important commands and features of Git , Github Actions and Linux that will help you in development. 

## 1. Git

### Introduction:

Git is open-source software and distributed version control system. It helps developers easily handle different versions of a source code. With it, you can know who did what, when, and why. Nowadays, Git has become a must-have tool for any developer, and knowing Git commands is essential for developers to use Git to its full potential. There are hundreds of Git commands, but only a few significant commands are used regularly.

Here you will learn the most helpful Git commands that will take you to the next level in development:

#### #1 git init

The git init command lets us create a new Git repository. This is the first command to start a new project in a GitHub repository. Go to the directory that contains your project files and run the git init command. A hidden .git subdirectory will be added to it.

##### Usage

`$ git init`

You can also provide a repository name with the git init command.

`$ git init <your repository name>`


#### #2 git clone

git clone creates a local working copy of the source code from a remote repository. When you clone a repository, the code will be automatically downloaded to your machine.

This command will add the original location as a remote location so you can pull changes from it and push changes to it if you have permission.

##### Usage

`$ git clone <git-repo-url>`


#### #3 git branch

git branch lets us add a new branch to an existing branch, view all existing branches, and delete a branch.

##### Usage

Create a new branch locally:

`$ git branch <branch-name>`

List all the local and remote branches:

`$ git branch -a`

View all branches and see which branch you’re currently working on:

`$ git branch or $ git branch --list`

Delete a branch:

`$ git branch -d <branch-name>`

Rename a branch:

`git branch -m <branch-name> <new-branch-name>`

#### #4 git checkout

The git checkout command allows us to switch to an existing branch or create and switch to a new branch. To achieve this, the branch you want to switch to should be present in your local system and the changes in your current branch should be committed or stashed before you make the switch. You can also use this command for checking out the files.

##### Usage

Switch to an existing branch:

`git checkout <branch-name>`

Create and switch to a new branch:

`git checkout -b <new-branch-name>`


#### #5 git add

The git adds command adds your changes in a file to the staging area where you can compare your local version and the version on the remote repository.

Before you commit your new or modified file, it should be added to the staging area by using the git add command.

##### Usage

Add specific files:

`$ git add <file-name-1> <file-name-2>`

Add all new, modified, and deleted files:

`$ git add -A`

Add modified and deleted files:

`$ git add -u`


## Flow Diagram
<img width="604" alt="githubflow" src="https://user-images.githubusercontent.com/61515279/218255242-29745406-14d6-40b7-aa98-2b8f5a7754cf.PNG">










