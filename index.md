# Git Workshop

## Initialize a Repository

    git init

## set identity

    git config --global user.name "name"
    git config --global user.email "email"

## stage file

    git add *
    git add <<filename>>

## untrack file

    git rm --cached <<filename>>

## generate new version

    git commit -m "message"
    i.e.: "Create index.md"

## display repository status

    git status

## display repository history

    git log
    git log <<filename>>

## display changes between staged and unstaged version of a file

    git diff <<filename>>

## display changes on line level

    git blame <<filename>>

## add new branch & switch to branch

    git branch <<branch name>>
    git checkout <<branch name>>

## push existing repository to github

    git remote add <<identifier>> <<ssh path>>
    i.e.: git remote add origin github.com:username/repository name.git
    git branch -M main
    git push -u origin main

## set url new, if remote url changes

    git remote set-url origin <<ssh path>>

## SSH keys

   ssh-keygen
   $<<filename>>
   $<<passphrase>>


