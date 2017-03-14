# GameDevCore
Game Dev Society UNSW - Core learning repository

## Welcome!
Welcome! Here, you will learn the core basics of Unreal Engine 4 that are relevant to both programmers and designers alike. Let's get started!

## Getting started with Git version control
You will need to clone (i.e. download) this repository to this computer to progress to the next section.
If you are an experienced programmer, you'll probably already know how to use Git. If this is the case, clone this repository and go to the next section. If not, then read on.

### What is Git?
Git is a version control system. It allows you to back up changes and revert to previous versions of your work with high granularity. More importantly, it allows multiple people to work on the same project together without running the risk of accidentally overwriting files. In simple terms, it is essentially a manual version of Dropbox/Google Drive, with a lot more control. 

### How do I use it?
This repository uses GitHub as the host for this Git repository. GitHub provides a very useful desktop application that makes it easy to get started. Follow these steps to clone this repository:
* Download the desktop application from https://desktop.github.com/
* Install the application and set up a GitHub account if you don't have one yet.
* Navigate to this repository's homepage (https://github.com/WeilonYing/GameDevCore) and click on Open in Desktop (screenshot: https://imgur.com/a/m5nAW)
* Pick a location to clone your repository to. GitHub Desktop should take care of the rest.
* Navigate to the repository in your file explorer. You should be able to find the file GameDevCore.uproject. Open it in Unreal Engine 4 (in Windows, double clicking it should do this).

If Unreal Engine 4 opens it without any issue, then you have successfully cloned this repository. Good job! Let's move onto the next section.

## Level Design Basics
When you first open this level, your screen should look something like this: https://imgur.com/a/3w6T1. If you're unfamiliar with the user interface of Unreal Engine 4, please watch this video tutorial here: https://docs.unrealengine.com/latest/INT/Videos/PLZlv_N0_O1gasd4IcOe9Cx9wHoBB7rxFl/w4XlBKeE46E/index.html.

Click on Play and start the game. You will be controlling a humanoid character. Unfortunately, he can't go very far, as the gap to the other side is too wide. Press Escape to exit the game once you're convinced that this is true :P

We need to add a platform to allow the player to get to the other side (https://imgur.com/a/f7mGc). Drag and drop a cube object from the class viewer (https://imgur.com/a/6zwQY), and place it over the gap to allow the player to get across. Use the arrow handles to fine tune its location (make sure you're in translate mode: http://imgur.com/a/rgcgT), and scale it to properly fill in the gap (http://imgur.com/a/Gxly3). Test your game once you're done.
