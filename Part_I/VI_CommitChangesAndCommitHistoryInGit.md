# Commit Changes and Commit History in Git
commit changes over time and track  them.

## What is commits?
New Changes added over time and we commit them after completing.
And we need a user friendly message with each and every commit

```
git commit -m "Message Of Commit"
```

## **Want to see History Of Commits**
```
git log (enter)
```
also give t 
- unique commit ID
- Author (username & email)
- Date & Time
- Commit Message
```
git log --oneline (used to show logs in short)
```
---
---
## *Wants to know about all changes in a specific file*
```
git blame <File_PAth>
```
```
git status(changes after commit)
```

## Staging Area
staged changes shown here , commit happens only on staged area.
```
git add .
``

Git Flow

Local File --->Staging Area--->Commit