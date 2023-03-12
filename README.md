# Git Alias

### **Set an Alias**

```
git config --global alias.[alias] "add -A"
```

### **Update git** (Update your git version)

```
alias.up update-git-for-windows
```

### **List Alias**

```
alias.alias config --get-regexp ^alias\.
```

### **git status**

```
st = status
```

### **git add -A + git commit -m**

```
acm = "!git add -A && git commit -m"
```

### **git branch** (Create your branch)

```
br = branch
```

### **git branch --show-current** (Show current branch)

```
brc = branch --show-current
```

### **git branch --delete** (Delete branch)

```
brd = branch --delete
```

### **git switch** (Change branch)

```
sw = switch
```

### **git switch -c** (Create the branch and switch to it)

```
swc = switch -c
```

### **git merge** (Merge branches)

```
mr = merge
```

### **git remote prune origin --dry-run** (See which local branches are no longer linked to the remote origin repository (does not delete))

```
prdry = remote prune origin --dry-run
```

### **git remote prune origin** (Deletes all unneeded branches from the remote repository)

```
pr = remote prune origin
```

### **git commit --amend -m** (I mistyped the last commit)

```
cma = commit --amend -m
```

### **git branch -m neu-branch new-branch** (I made a mistake when naming my branch)

```
brn = branch -m
```
