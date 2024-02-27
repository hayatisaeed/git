# Git Cheat-Sheet

## Initial Configs

### Set name for all projects
``` bash
git config --global user.name {username}
```

### Set email for all projects
``` bash
git config --global user.email {email}
```

### Set name in current project
``` bash
git config --local user.name {username}
```

### Set email in current project
``` bash
git config --local user.email {email}
```

## Start Project

### Initialize a local project
``` bash
git init {project name}
```

### Sync a local project with a remote server origin
  ``` bash
git remote add origin {url}
```

### Bring a project from a remote server to local computer
``` bash
git clone {url}
```

## Daily things

### See all edited files and added files (compared to the last commit)
``` bash
git status
```

### Bring a file to the staging area and make them ready to commit
``` bash
git add {file name}
```

### Brgin all edited files to staging area
``` bash
git add .
```

### See differences between a file compared to last stage
``` bash
git diff {file name}
```

### See difference between a file compared to last commit
``` bash
git diff --staged {file name}
```

### See difference between current files and last commit
``` bash
git diff HEAD
```

### Make a new commit from files in staging area
``` bash
git commit -m "details of this commit"
```

### Remove a file from repository
``` bash
git rm {file name}
```

### Save Unfinished changes without creating a new commit
``` bash
git stash
```

### Apply saved state (stashed stuff) of the project
``` bash
git stash apply
```

### Remove a stash
``` bash
git stash drop
```

## Work with branches

### See all branches of the repository
``` bash
git branch
```

### See all repository branches (including remote branches)
``` bash
git branch -a
```

### Create a new branch
``` bash
git branch {branch name}
```

### Checkout an existing branch
``` bash
git checkout {branch name]
```

### Create a new branch and checkout that
``` bash
git checkout -b {branch name}
```

### Merge a branch with current branch
``` bash
git merge {branch name}
```

### Merge first branch to second branch
``` bash
git merge {first branch} {second branch}
```

### Rebase current branch with a branch
``` bash
git rebase {branch name}
```

### Delete a branch
``` bash
git branch -d {branch name}
```

# Communicate with Remote project

