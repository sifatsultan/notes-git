### Branching
Create a new branch the following way.
```bash
git checkout -b branchname
```
Push the branch you made to your server repo the following way.
```bash
git push origin branchname
```
So once you are happy with the branch, add commit and just merge it by checking out to master and merging the branch like this.
```bash
git checkout master
git merge branchname
git branch -d branchname
```

Remove branches in the remote that has been removed from local
```bash
git fetch --prune
git push origin --delete test
```
