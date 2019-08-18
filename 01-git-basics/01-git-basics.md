# 01. Git-Basics 
Basic Commands:

![basic-cmnds](C:\temp\git\Git-Studies\01-git-basics\basic-cmnds.jpg)



Data Transfer in Git

![data-transfer-git](C:\temp\git\Git-Studies\01-git-basics\data-transfer-git.jpg)



##  1.1 Getting a Git Repository

`git init`

Initializing a Repository in an Existing Directory

`git add *.java`

add to index (stage)

`git commit -m 'initial project version'`

add to local repo

`git clone https://github.com/abushonn/SmartGitDemo.git`

Cloning an Existing Repository



##  1.2 Recording Changes to the Repository

`git status`

To determine which files are in which state.

`git add README`

In order to begin tracking a new file

`cat .gitignore`

Ignoring Files

`git diff`

To see what you have changed but not yet staged

`git diff --cached`

To see what you have staged so far

`git commit`

Commit; message will be edited in the configured editor (default - vim) 

`git commit -m "Story 182: Fix benchmarks for speed"`

Commit with message

`git commit -a -m 'automatically adds not staged files'`

Skipping the Staging Area.

`git rm a.txt`

To remove file from your tracked files (remove it from your staging area) and then commit. 

