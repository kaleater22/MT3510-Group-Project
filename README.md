# MT3510-Group-Project
Repository for the MT3510 pure team project

# Getting Started with GitHub

GitHub is a website that stores your code online and tracks changes over time. Here's how to get started.
You can either interact with git through the GitBash terminal or through git desktop (I think this is easier) , which you use is personal preference and won't change anything.

---

## 1. Set Up
If you haven't already:
- Create a free account at [github.com](https://github.com)
- Download and install [Git](https://git-scm.com/downloads) on your computer 

---


## 2. Prefer Clicking Over Typing? Use GitHub Desktop

**GitHub Desktop** lets you do everything with buttons and menus instead of commands.

- Download it at [desktop.github.com](https://desktop.github.com)
- Sign in with your GitHub account
- Open your repository and you'll see a visual interface to:
  - **Commit** your changes with a description
  - **Push** with one click
  - **Pull** the latest changes just as easily

---

## 3. Pushing vs. Pulling

**Pushing** means uploading your changes from your computer to GitHub.
Think of it as saving your work to the cloud so others can see it (or so you don't lose it).

```bash
git push
```

**Pulling** means downloading the latest changes from GitHub to your computer.
You'd do this if you're working on multiple computers, or if a teammate made changes you don't have yet.

```bash
git pull
```

A simple way to remember it: you **push** your work up, and **pull** others' work down.

---

## 4. The Basic Workflow
Every time you make changes, follow these three steps in your terminal:

```bash
git add .                        # Stage your changes
git commit -m "describe change"  # Save a snapshot
git push                         # Upload to GitHub
```


## 5. What conflicts are 

A conflict happens when two people change the _same_ lines in a file and Git can’t decide which change to keep. When that happens Git will pause and mark the file for you to fix.

How to avoid conflicts

Pull (or pull --rebase) before you start and before you push.

Work in short-lived branches and make small commits (i.e. work within your own code cell).

Don’t edit the exact same lines as someone else and coordinate on larger changes.

### If a conflict happens:

Open the file — Git shows <<<<<<<, =======, >>>>>>>.

Edit to pick/merge the correct lines and remove the markers.

git add <file>, git commit, then git push.
If unsure, ask a teammate !

