---
layout: post
title:      "Command Line Cheatsheet"
date:       2018-11-07 15:13:52 -0500
permalink:  command_line_cheatsheet
---

Recently, I’ve been getting more comfortable using the command line in my development workflow.  I decided to write down some common commands for easy reference.  

### Commands
---
<br>
 **Print Working Directory**
```
$ pwd
```

Pwd stands for **P**rint **W**orking **D**irectory.  It outputs the path of your current directory in your terminal.

<br>

**Change Directory**
```
$ cd filename
```

Cd stands for **C**hange **D**irectory.  You can change from the directory you’re in to the directory you write after the letters "cd"

<br>


**Go Up One Level**

```
$ cd ../
```

This comand will take you up one directory level.  Basically it goes back one folder.  Be sure there is a space between ```cd``` and ```../``` otherwise this command will not work. 

<br>


**Go Up Two or More Levels**
```
$ cd ../../../
```

You can use multiple ```../``` to go back further!

<br>

**Make a New File**
```
$ touch newfilename
```

Creates a new file within the current directory with the name you specify after “touch”.

<br>

**Make a New Folder/Directory**

```
$ mkdir newdirectoryname
```

Creates a new folder/directory with the name you specify after “mkdir”.

<br>


**List Files**

```
$ ls
```

This command names all of the files within the current folder/directory.

<br>


**Remove a File**

```
$ rm filename
```

This removes the file from the directory.   It's irreversible, so use this command with caution.

<br>


**Remove a Folder/Directory**
```
$ rmdir directoryname
```

This command will remove a directory, again be sure you want to remove the directory since it’s irreversible.

<br>

**Clear the Terminal**
```
$ clear
```

This command will clear your terminal screen.

<br>

---

#### ☆☆ Bonus ☆☆

 **Up/down arrow**

Pressing the up/down arrow will scroll through the previous commands you input to the terminal.  
<br>

 **Tab**

Pressing tab while typing out a file name will autocomplete the file name in the terminal.


---

<br>

The command line is something we use a lot as developers.  As you use and commit these commands to memory, they will become second nature.  I hope this cheatsheet is as helpful to you as it is to me.  

<br>
Happy Coding!

