# git-basic


#### create branch
```
git branch -a
git branch new-branch-name
```

#### delete branch

```
git push origin -d branch-name
```

#### delete branch
```
git checkout main
git merge --squash branch-name
git commit
git push
```

#### unlock .git
```
sudo chmod -R 755 .git
```

#### pull from origin into branch
```
git fetch
git rebase origin
```
