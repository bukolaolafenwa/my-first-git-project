# My First Git Project

This HTML and CSS project was used to teach beginner web development students how to track changes and collaborate using Git and GitHub.

**Instructor:** Bukola Ruth Olafenwa  
**Designation:** Full Stack Web Development Instructor  
**Academy:** Tech Studio Academy

## Project files

- `index.html` contains the practice webpage.
- `style.css` contains its styling.

We changed these files throughout the lesson to see how Git records different versions of a project.

## What we practised

- Creating a local Git repository and making commits
- Connecting the repository to GitHub and pushing changes
- Creating and switching between branches
- Merging branches into `main`
- Resolving a merge conflict
- Pulling changes from GitHub

## Branches used

| Branch | Purpose |
| --- | --- |
| `main` | The primary branch that received the completed changes |
| `add-skills` | Adding skills content and practising a merge |
| `subject` | Making another change and merging it into `main` |
| `update` | Changing a heading differently from `main` to practise resolving a merge conflict |

## Commands used in the lesson

| Command | What it does |
| --- | --- |
| `pwd` | Shows the current folder in the terminal |
| `git init -b main` | Creates a local Git repository with `main` as its starting branch |
| `git status` | Shows the current branch and the state of changed files |
| `git add .` | Stages changes in the current folder and its subfolders |
| `git commit -m "message"` | Saves staged changes in a commit |
| `git log --oneline` | Shows a short commit history |
| `git remote add origin URL` | Connects the local repository to its GitHub repository |
| `git remote -v` | Shows the connected remote repository |
| `git push -u origin main` | Pushes `main` to GitHub and sets its upstream connection |
| `git push` | Pushes later commits to the connected branch on GitHub |
| `git branch` | Lists local branches and marks the current branch with `*` |
| `git switch -c branch-name` | Creates a branch and switches to it |
| `git switch branch-name` | Switches to an existing branch |
| `git merge branch-name` | Merges the named branch into the current branch |
| `git pull origin main` | Brings changes from GitHub's `main` branch into the current branch |

## Merge conflict exercise

We made different changes to the same heading on `main` and `update`. Running `git merge update` while on `main` produced a conflict in `index.html`.

We chose the final heading, removed the conflict markers, staged the resolved file, committed the resolution, and pushed the result to GitHub.

This repository is a classroom learning exercise.