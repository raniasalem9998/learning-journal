# Git 
is a system that allows you to revisit various versions of a file or set of files by recording changes.
***
It is a great tool to edit your files and track all actions you make clean and clear. it also allows you to code from your laptop without needing to connect to cloud.
***
your file can be in one of the three stages :
* committed
* modified 
* staged
> to check file status use **git status**
#
1- First is cloning: use the command **git clone URL** 
- Use **cd** and **ls** to move in the file.
- Type **code .** .
> VS code will open for you to start your work!
---
***note that :***
 The local Git repository has three components:
* Working Directory: The actual files reside here.
* Index: The area used for staging.
* Head: Points to the most recent commit.
--
- saving changes can be tracked or not.
- to track a file use **git add filename**.
- commiting a file and save it use **git commit m-(why?)
> **git commit -a** is to save all changes.

- at the end you will push it and sync it with github by **git push origin master** 
- you can see remote using **git remot -v** also edit them.
- you can rename **git remot rename** or remove **git remot rm**.
