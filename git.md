# Using Git
#####
Basically just containing a list of commands and what they do.

#### Extra Note:
Look into creating remote to GitHub through CLI.

### Setup
Initialize a repository, default creates a master branch.
```
git init
```

Adding remote origin.
```
git remote add NAME https://github.com/OWNER/RESPOSITORY.git
git remote set-url NAME https://github.com/OWNER/REPOSITORY.git
```

Creating branches.
```
git branch BRANCE_NAME BRANCH_TARGET
```

Switching branches.
```
git checkout BRANCH_NAME
```
**NOTE: The above two can be used in conjuction to both create a new branch and swich to it**

Add files to commit stack.
```
git add .
```

View commit stack (tree).
```
git log
```

Commit files to branch.
```
git commit -m 'MESSAGE HERE'
```

Set push and set upstream
```
git push --set-upstream origin master
```

