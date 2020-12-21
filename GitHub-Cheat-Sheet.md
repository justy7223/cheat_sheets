# GitHub Cheat Sheet

# Table of Contents
* [Setup Git](#Setup-Git)
* [Setup Repository](#Setup-Repository)
* * [No Local Code](#Pulling/Downloading-source-from-repository-(No-local-code-created))
* * [Local Code Already Created](#Pushing/Uploading-local-source-to-repository-(Local-code-already-created))
* [Working With Changes](#Working-With-Changes)
* * [Pushing Changes](#Pushing/Uploading-changes-to-repository)
* * * [Managing Push Conflicts](#Managing-Push-Conflicts)
* * [Pulling Changes](#Pulling/Donwloanding-changes-to-local-project)
* * * [Managing Pull Conflicts](#Managing-Pull-Conflicts)
* [Links](#Links)
* [Images](#Images)
* [Coding & Syntax](#Coding=&-Syntax)
* [Tables](#Tables)
* [Blockquotes](#Blockquotes)
* [Lines](#Lines)
* [Misc Formatting](#Misc-Formatting)

***
***
# Setup Git (Configuring Local Git)
> `git config --global user.name "[firstname lastname]"`  
> *set name to use for credit during push/pull/commits/etc for all local repositories*  

> `git config --global user.email "[email]"`  
> *set email to use for credit during push/pull/commits/etc for all local repositories*

> `git init`  
> *set up current directory as a git repository*

***
***
# Setup Repository
When setting up a repository in GitHub, you need to setup the base repository folder via GitHub web interface before any initial source can be uploaded/downloaded.  

Below steps assume basefolder has been created:  
## Pulling/Downloading source from repository (No local code created)
> `git clone https://github.com/UserName/repository.git`  
> *copies repository files to local directory*

## Pushing/Uploading local source to repository (Local code already created)
> `git add .`  
> *adds all files in the local directory to the list of files to push/upload*  
> `git commit -m "Initial source upload"`  
> *sets the commit message to use when pushing these files*  
> `git --set-upstream https://github.com/UserName/repository.git`  
> *pushes files in local directory to repository for initial upload*

***
***
# Working With Changes
## Pushing/Uploading changes to repository
> `git status`  
> *checks the current directory for any local changes since last push*  
> `git add index.js index.html`  
> *adds files to the list of files to push, can use . like shown above for all changed files*  
> `git commit -m "Adding Home Page and supporting JS"`  
> *sets the commit message to use when pushing these updates*  
> `git push`  
> *pushes local changes to repository.  
## Managing Push Conflicts

## Pulling/Downloading changes to local project
> `git pull`  
> *pulls/downloads repository changes to the local project*
## Managing Pull Conflicts


