# Lab 2: Pushing and Cloning a Repository

Name: Pushpendra Singh
Roll No: 2410303367
Student ID: BCS2024376
Section: D
Course: B.tech(CSE)
Course: BCS554 - HTML & CSS Development Lab
University: Invertis University, Bareilly 

_______________________________________________________________

Aim
Create a bare remote repo, push the commits to it and clone it into a new folder.

Theory
- A remote is a copy of the repo stored somewhere else (another folder, GitHub, a server).
- A bare repository (git init --bare) has no working files, only the history. It is used as a central shared repo.
- git remote add origin <path-or-url> gives the remote a short name. origin is the usual name. git remote -v lists remotes with their addresses.
- git push origin main uploads your commits to the remote branch. The branch may be called main or master, so check with git status.
- git clone <repo> <folder> copies a whole repo with its complete history and sets origin automatically.
- After cloning, git log --oneline shows the same commits as the original.

Files in this folder
- commands.txt: Git commands for Tasks 1 to 3.

How to check
Run the commands inside git-practice/html-lab. Screenshot the terminal output of each task.