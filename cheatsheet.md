# Git cheatsheet

### Start a new project

```shell

$ mkdir project_name
$ git init
$ touch readme.md
$ git add readme.md
$ git commit -m "initial commit"

```
$ git status
$ git add <something>
$ git status
$ git commit -m "I made some changes"



### Share my work wih the world

First, create a github repo.

```shell

$ git remote add origin git@github.com:<github username>/<name of repository>.git
$ git push -u origin master

```