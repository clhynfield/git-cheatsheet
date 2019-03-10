# git-cheatsheet

Helpful tips for using git.

## Create a new Git repository

```bash
$ git init
$ git add .
$ git commit -m 'Initial commit'
```

## Add a .gitignore

https://github.com/github/gitignore


## Clone an existing project

```bash
# Use ssh
$ git clone git@github.com:ssherwood/git-cheatsheet
```

## Stashing changes

```bash
# Push all uncommitted changes to "stash" stack
$ git stash

# Restores the top of the "stash" stack 
$ git stash pop
```

## Reset 

```bash
# Abort the current uncomitted changes
$ git reset --hard
```
