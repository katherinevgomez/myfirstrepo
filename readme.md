# My Git Cheatsheet

##Creating a Git Repo

In the folder you want to create a repo, do the following command in terminal

```
git init
```

**Always check that you are not already in a repo by using git status**
---
##Adding Files to Staging

Staging is files that being tracks to be commited

use git statuts to see which files are untracked(red) or in staging(green)

git status
```

three ways to add files to staging

-add one file at a time `git add <filename>`
-add all files in the repo `git add -A`
- add all files in my current folder with `git add .`

## Committing Files to our repo

```
git commit -m "some decriptive text"
```
**If you forget the -m, you'll end up in vim, to exit type ":wq"**