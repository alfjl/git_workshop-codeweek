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


