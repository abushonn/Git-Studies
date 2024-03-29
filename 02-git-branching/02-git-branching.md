# 02. Git-Branching
Why branches:

![br-rules](./br-rules.jpg)



##  2.1 What a Branch Is



![br-01](./br-01.jpg)

Commit - node representing a committed change (data + metadata).

Commits are organized as a linked list ( a commit-node points to the previous commit) .

A commit is created for the following:

`$ git add README test.rb LICENSE`

`$ git commit -m 'initial commit of my project'`

A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is `master`. 

If you create a new branch a new pointer is created for you:

`$ git branch testing`

![br-02](./br-02.jpg)

How does Git know what branch you’re currently on? It keeps a special pointer called HEAD.

To switch to an existing branch:

`$ git checkout testing`

Update and commit (in branch `tesing`):

`$ edit test.rb`

`$ git commit -a -m 'made a change'`





## 2.2 Basic Branching and Merging

Branching and merging use-case:

1. `Do work on a web site.`
2. `Create a branch for a new story you’re working on.`
3. `Do some work in that branch.`

Urgent another issue; hotfix is needed. 

1. `Switch back to your production branch.`
2. `Create a branch to add the hotfix.`
3. `After it’s tested, merge the hotfix branch, and push to production.`
4. `Switch back to your original story and continue working.`



Original story development:

![br-mrg-01](./br-mrg-01.jpg)

Urgent issue. Trivial merge:

![br-mrg-02](./br-mrg-02.jpg)



Switch back to the original story; development and merge.

![br-mrg-03](./br-mrg-03.jpg)







## 2.3 Branch Management

`git xxx`

xxxx

## 2.4 Branching Workflows

`git xxx`

xxxx

## 2.5 Remote Branches

`git xxx`

xxxx

## 2.6 Rebasing

`git xxx`

Not now, somewhen in the future.




