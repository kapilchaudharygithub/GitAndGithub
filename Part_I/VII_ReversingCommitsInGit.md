# Reverting Back
Mechanism to revert back from Falty code to old version
Linked List --->Head(latest version/commit)
## 1. Idea: To change your head from latest faulty to previous working one
```
git reset --hard [old Commit id]
git push -f
```

### Problem 
Losing the faulty one commits due to linear flow

## Reverting the changes from file
It reverts the changes, if something is added then it deletes it ,and vice-versa
```
git revert <File_Path>
```