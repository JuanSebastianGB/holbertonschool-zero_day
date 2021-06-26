# 0x03-git

### Learning Objectives

- What is source code management
- What is Git
- What is GitHub
- What is the difference between Git and GitHub
- How to create a repository
- What is a README
- How to write good READMEs
- How to commit
- How to write helpful commit messages
- How to push code
- How to pull updates
- How to create a branch
- How to merge branches
- How to work as collaborators on a project
- Which files should and which files should not appear in your repo

### Requirements

- A README.md file at the root of the holbertonschool-zero_day repo, containing a description of the repository
- A README.md file, at the root of the folder of this project (i.e. 0x03-git), describing what this project is about
- Do not use github’s web ui, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web ui). you won’t be able to perform many of the task requirements on the web ui, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
your answer files should only contain the command, and nothing else

### Tasks
0. Create and setup your Git and GitHub account
1. Repo-session
2. Coding fury road
| Content 1 | Content 2 |
|-----|------|
| [dir c](c) | [dir bash](bash) |


### MORE INFO

- install Git if not installed
```shell
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```

### Basic usage

```shell
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
```