# Git-Commands
Git commands cheat sheet


#Git Basics

Setup
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Create a New Repository
```sh
git init
```

Clone an Existing Repository
```sh
git clone <repository-url>
```

#Working with Changes

Check Status
```sh
git status
```

Add Changes
```sh
git add <file>
git add .           # Add all changes
```

Commit Changes
```sh
git commit -m "Commit message"
```

Remove Files
```sh
git rm <file>
```

Move/Rename Files
```sh
git mv <old-name> <new-name>
```

#Branching and Merging

Create a New Branch
```sh
git branch <branch-name>
```

Switch to a Branch
```sh
git checkout <branch-name>
```

```sh
git checkout -b <branch-name>
```

