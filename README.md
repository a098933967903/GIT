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

Checking whether config set or not
```
$ git config --global user.name 
$ git config --global user.email 
```
Checking the status
```
$ git status
```


## Set up Git

```
$ git config --global user.name "<user_name>"
$ git config --global user.email <mail>
```
* git config is a tool
* --global parameter mean to publish, everyone can see the information that you set

## Download file what you want in gethub

```
$ git clone <file_route>
```
file_route mean that you place a route

## push the file to github
first check the status
```
 git status
```
if show red file, it mean it is new file 
and you can push it to Github
* adding file to the buffer
```
$ git add <file_name>  // add singular file
$ git add . // adding all file also you can comment $ git add --all
```
* to save the file 
```
$ git commit -m "<endscript>"     //commit have write something down meaning
```
* Push file
```
$ git push
```




