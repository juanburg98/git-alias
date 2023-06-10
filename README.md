# Git Alias

### Set an alias


```ruby
git config --global alias.[alias] "add -A"
```

### Update git
Update your git version

```ruby
up = "update-git-for-windows"
```

### List alias

```ruby
alias = "config --get-regexp ^alias\."
```

### git status

```ruby
st = "status"
```

### git add -A + git commit -m

```ruby
acm = "git add -A && git commit -m"
```

### git branch
Create your branch

```ruby
br = "branch"
```

### git branch --show-current
Show current branch

```ruby
brc = "branch --show-current"
```

### git branch --delete
Delete branch

```ruby
brd = "branch --delete"
```

### git switch
Change branch

```ruby
sw = "switch"
```

### git switch -c
Create the branch and switch to it

```ruby
swc = "switch -c"
```

### git merge
Merge branches

```ruby
mr = "merge"
```

### git remote prune origin --dry-run
See which local branches are no longer linked to the remote origin repository
(does not delete)

```ruby
prdry = "remote prune origin --dry-run"
```

### git remote prune origin
Deletes all unneeded branches from the remote repository

```ruby
pr = "remote prune origin"
```

### git commit --amend -m
I mistyped the last commit

```ruby
cma = "commit --amend -m"
```

### git branch -m neu-branch new-branch
I made a mistake when naming my branch

```ruby
brn = "branch -m"
```
### git restore
Undo a modified file

```ruby
res = "restore"
```
