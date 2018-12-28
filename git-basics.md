# Git Basics

## Initialising and cloning a repo

Firstly open a Terminal window and cd into the required directory

>     cd path/to/directory

* Initiate a new git repository

>     git init .

* To clone (check out) an existing repo

>     git clone https://example.co.uk/example.git

## Adding files and making a commit

* Add all files not currently staged

>     git add .

* Add a single file not currently staged

>     git add *filename*

* Commit all files (-a) and add a message (-m)

>     git commit -a -m "commit message goes here"

## Branching

* To create a new branch and perform a checkout in one command

>     git checkout -b *branch-name*

* To create a new branch without checking it out

>     git branch *branch-name*

* To checkout an existing branch

>     git checkout *branch-name*

* To merge commited changes from a branch into master

>     git checkout master
>     git merge *branch-name*

* To delete a branch

>     git branch -d *branch-name*

## Working with remote repos

* Add a remote repo

>     git remote add origin remote repository URL

* Verify the remote repo URL

>     git remote -v

* To pull latest code from a remote repo

>     git pull origin master

* To push code to a linked remote repo

>     git push origin master
