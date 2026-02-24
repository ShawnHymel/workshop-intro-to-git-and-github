# Introduction to Git and GitHub for Beginners Workshop

Welcome to the Intro to Git and GitHub workshop! Read through this guide and perform the hands-on activities to complete the workshop. Git is a type of version control system that allows you to keep a history of your work so you can experiment safely, recover from mistakes, and collaborate without overwriting changes from other team members.

> **Note**: The two popular methods for working with Git are the command line interface (CLI) tools and the graphical user interface (GUI). The GUI is easier to understand and use, especially for newcomers and simple projects. The CLI tool has a steeper learning curve but is generally more powerful. I'll put both in this guide, and you can choose whichever one you like better.

## Overview

### What is Version Control?

Version control is a system for tracking changes to files over time so you can see what changed, when it changed, and restore earlier versions if needed. Instead of keeping multiple copies of files with names like *my_project.py*, *my_project_v2.py*, and *my_project_final_FINAL.py*, a version control system maintains an organized history of a project. This makes it easier to experiment safely, recover from mistakes, and collaborate with others without overwriting each other’s work. Version control is especially useful in programming, where even small changes can introduce bugs and teams often need to work on the same codebase at the same time.

### What is Git?

Git is a version control system that runs locally on your computer and records snapshots of your project called commits. Each commit represents the state of your files at a particular moment in time, allowing you to review changes or return to earlier versions. What makes Git unique among version control systems is that it is distributed, meaning every copy of a repository contains the full project history rather than relying on a single central server. This makes Git fast, flexible, and reliable, and allows developers to work offline and experiment safely using features like branches. Services like GitHub build on Git by providing online storage and collaboration tools for Git repositories.

> *Did you know?* Git was originally created by Linus Torvalds (the creator of Linux) in 2005 after the free license of BitKeeper (the version control software being used for Linux development) was revoked. Torvolds then set out to make something better. Feel free to read the full history [here](https://en.wikipedia.org/wiki/Git#History).

While Git was originally designed to help programming teams keep track of changes and merge files from multiple developers, it works with any type of file. While you might not get the nice features of e.g. seeing exactly what line changed for each commit, there's nothing stopping you from committing your CAD design files. In fact, you should consider using a version control system for all your projects. If you use a cloud-based version control system (e.g. GitHub), you are backing up your work in case something happens to your local copy (such as your laptop catching on fire).

### What is GitHub?

GitHub is an online platform that hosts Git repositories and makes it easier to share code and collaborate with others. While Git itself runs locally on your computer and tracks the history of your project, GitHub stores a copy of that project on the internet so you can back it up, access it from multiple computers, and work with other people. GitHub also adds collaboration features on top of Git, such as pull requests, code reviews, issue tracking, and project documentation. In simple terms, Git is the tool that tracks changes, and GitHub is a service that stores Git repositories online and helps people work together on them.

> **Note**: GitHub isn't the only place to host Git repositories (another option is [Bitbucket](https://bitbucket.org)), but it's the most popular, which makes it the easiest place to start.

### Terminology

Git has some common phrases that can be a little confusing if it's your first time. Feel free to 
come back to this glossary if you need to look up a definition.

 * **Branch** - A separate line of development that lets you work on changes without affecting the main project.
 * **Clone** - Downloading a complete copy of a repository from the internet to your computer.
 * **Commit** (`git commit`) -  A saved snapshot of your project at a specific point in time. Each commit records changes and includes a message describing what was done. Think: save with history.
 * **Commit Message** - A short description of what changed in a commit.
 * **Git** - A version control system that runs locally on your computer and tracks the history of a project using snapshots called commits.
 * **GitHub** - A website that hosts Git repositories online so you can back up your work and collaborate with others.
 * **Local Repository** - The copy of the repository stored on your computer where you edit files and make commits.
 * **Main Branch (main)** - The primary or stable version of the project.
 * **Merge** - Combining changes from one branch into another.
 * **Pull** (`git pull`) - Downloading changes from the remote repository to your computer.
 * **Pull Request (PR)** - A request on GitHub to merge changes from one branch into another. Pull requests allow changes to be reviewed before merging.
 * **Push** (`git push`) - Uploading commits from your computer to the remote repository.
 * **Remote Repository** - The copy of the repository stored online (for example on GitHub).
 * **Repository (Repo)** - A project folder that Git tracks, including the files and their full change history. Think: project folder + history.
 * **Staging** (`git add`) - Selecting which changes will be included in the next commit.
 * **Working Directory** - The files on your computer that you are currently editing.
 * **Version Control** - A system for tracking changes to files over time so you can review changes and restore earlier versions if needed.

## Part 1: Basic Flow






