# GIT
HowToUseGit


## Frist install the git
GIT [download](https://git-scm.com/downloads)

## Generating the ssh key

```
$ ssh-keygen -o -t rsa -C "your@email.com"
```
then, it will product the public-key in your computer, your need to find it and paste it

pasted place that locate in setting 

![ssh key](https://user-images.githubusercontent.com/99935573/163659014-b62990e0-20fd-4d8d-a640-0f25538809fa.jpg)


## Check 

Checking the git where it install or not
```
$ git --version
```


## Set up Git

```
$ git config --global user.name "<user_name>"
$ git config --global user.email <mail>
```
* git config is a tool
* --global parameter mean to publish, everyone can see the information that you set
