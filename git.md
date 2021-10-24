# Basic GIT commands

### To clone a repo
```
$ git clone git@github.com:priyankabellary/til.git
```

### To commit a change
```
$ git commit -m 'new change'
$ git commit -m 'title' -m 'body'
```

### To push the changes
```
$ git push
```

### To create a branch
```
$ git checkout -b <branch_name>
```

### To list branches
```
$ git branch
```

### To push a branch
```
$ git push --set-upstream origin readme
```

### To delete a branch
```
git branch -D readme
```

### To change a branch
```
$ git checkout <branch_name>
```

### To merge a branch
```
$ git merge <branch_name>
```

### To pull latest changes
```
$ git pull
```

### To check status of current branch
```
$ git status
```

#### To see changes
```
$ git diff
$ git diff HEAD README.md
$ git diff HEAD~1 README.md
$ git diff HEAD~2 README.md
```

### To add files to git
```
$ git add .
$ git add bash.md
```

### To remove files from git
```
$ git reset bash.md
```

### To list commit logs
```
$ git log
$ git log -1
$ git log -2
```
