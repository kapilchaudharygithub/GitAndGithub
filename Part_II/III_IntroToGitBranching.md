## Check Branch
```
git branch
```
## Add new Branch
```
git branch <branch_Namwe>
```

## Switch to another branch
```Way-1
git checkout <Branch_Name>
```
```Way-2
git checkout -b <Branch_Name>
```


## Creating branch on remote
```
git push --set-upstream origin <Branch_Name>
```

## Merge new branch to main
-Steps
-- Go in main
-- Check branch
-- merge
```
git checkout main
git branch
git merge origin/<NewBranchNameToAdd>
git push
```

``` Way-2
Create new pull request
compare-->from branch
base-->to branch
add title , desc
go to file changes-->conversation click merge(on server)
git checkout main
git pull(sync with server)

```

### Branching name convention
- feature: "feat/featureName"
- bug fix: "bug/bug_name"
- work in progress : "wip/workName"
- experiment: "junk/random"
junk: throwaway branch created to experiment



### rebase
maintain history well
but increases a lot of commit history
done in special cases only

```
git rebase <branch_name>
git push
```

### git stash
get temporary code changes on remote without  adding new changes to remote from local
```
git stash
git pull
git stash apply 
```