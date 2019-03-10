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
# using ssh protocol
$ git clone git@github.com:ssherwood/git-cheatsheet
```

## Stashing changes

```bash
# push uncommitted changes to "stash" stack
$ git stash

# restore the top of the "stash" stack 
$ git stash pop
```

## Reset 

```bash
# abort current uncomitted changes
$ git reset --hard

# restore a specific file to its original state
$ git checkout -- README.md
```
