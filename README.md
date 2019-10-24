Simple repository we used to demonstrate how to make new branches, pull request and merge.

Checkout on: https://blog.gusflopes.dev/github-starting-branches/

## Commands used

### Starting the repository
```
git init
touch file1.md
git add .
git commit -m "initial commit"
git remote add origin git@github.com/gusflopes/gitpost.git
git push -u origin master
```


### Branch
```
git checkout -b newbranch
touch file2.md
git add .
git commit -m "message"
git push -u origin newbranch
```

### Pull request & Merge
We done this directly on the Github website. You can checkout on this repository at `Commits`

### Cleaning up
Just go back to the `master` branch and deleting the `newbranch`:
```
git checkout master
git branch -d newbranch
```

## Thanks
That's it!
Checkout on my blog were i explain better these commands and show you a GIF video of all we done.

**Gustavo Lopes**