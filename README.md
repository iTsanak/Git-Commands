# Git-Commands
Git commands cheat sheet


# Git Basics

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

# Branching and Merging

Create a New Branch
```sh
git branch <branch-name>
```

Switch to a Branch
```sh
git checkout <branch-name>
```

Create and Switch to a New Branch
```sh
git checkout -b <branch-name>
```

Merge a Branch
```sh
git checkout <target-branch>
git merge <source-branch>
```

Delete a Branch
```sh
git branch -d <branch-name>
```

# Remote Repositories

Add a Remote Repository
```sh
git remote add <remote-name> <remote-url>
```

Fetch Changes from Remote
```sh
git fetch <remote-name>
```

Push Changes to Remote
```sh
git push <remote-name> <branch-name>
```

Pull Changes from Remote
```sh
git pull <remote-name> <branch-name>
```

# Inspecting Changes

Show Commit History
```sh
git log
```

Show Changes in Files
```sh
git diff
```

Show a Specific Commit
```sh
git show <commit-hash>
```

# Stashing Changes

Stash Changes
```sh
git stash
```

Apply Stashed Changes
```sh
git stash apply
```

List Stashes
```sh
git stash list
```

# Resetting and Reverting

Undo Changes in Working Directory
```sh
git checkout -- <file>
```

Reset to Last Commit
```sh
git reset --hard HEAD
```

Revert a Commit
```sh
git revert <commit-hash>
```

# Tagging

Create a Tag
