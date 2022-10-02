---
layout: post
title:      "Git Commands Cheatsheet"
date:       2022-10-01 15:13:52 -0500
permalink:  git_commands_cheatsheet
---

## Git Workflow
---
Having an idea of the git workflow has been beneficial for me remembering what each command does. 
1.  Begin with with ```git init``` or ```git clone``` which will create a new repository locally or pull down a project from the web.  

2. Make changes in our working directory locally.  

3. ```add``` these changes to our "staging area" where we list changes made in the working directory.  

4. ```commit``` the changes and (optionally) add a message to reference the work added to the "staging area".  

5. ```Push``` the changes in our local working directory to the repository where git permamently stores the changes as different versions of the project. 

## Creating Repositories
---
 **Git Init**
```
$ git init [project name]
```
This command creates a new empty repository within the current directory on your local computer.


**Git Clone**
```
$ git clone [url]
```

Downloads a project from online.  If you are using Github, this is the command to download the project locally.

## Making Changes
---

**Status**

```
$ git status
```

This command tells you what branch you're on as well as if the files have been added to the "staging area" or the repository via "git add" or "git commit" respectively.

**Git Diff**

```
$ git diff
```

Shows the differences in a file between the "working directory" and the "staging area"

**Git Add**
```
$ git add .
```

Adds all the changes made to a file to the "staging area"


**Git Commit**
```
$ git commit -m "[descriptive message]"
```
Takes a snapshot of the file and adds a message.  The message must be in quotation marks, written briefly in the present tense.

**Git Push**
```
$ git push -u [alias][branch]"
```

Uploads all local branch commits to versioning website, i.e Github.  In my experience, the alias name has been "origin", but you can name it whatever you like. 

For example: 
```
$ git push -u origin master"
```

## Group Changes
---

**Git Branch**

```
$ git branch
```

Lists all branches that are in the current repository, the branch you are working on will be highlighted with an asterick (*).

**Create a New Branch**

```
$ git branch [branch-name]
```

Creates a new branch

**Switching Branches**

```
$ git checkout [branch-name]
```
Switches to the specified branch name


**Merging Branches**

```
$ git merge [branch]
```
Combines the specified branch's contents into the current branch
---
<br>

