# Real Git Scenarios

Real-world problems and their solutions.

---

## Switch Branch with Changes

Error:

```
Your local changes would be overwritten
```

Solution:

```bash
git stash
git switch branch-name
```

---

## Undo Last Commit

```bash
git reset --soft HEAD~1
```

---

## Recover Deleted Commit

```bash
git reflog
git reset --hard <commit-hash>
```

---

## Fix Merge Conflict

Steps:

1. Open file
2. Resolve conflict
3. Remove markers
4. Add & commit

---

## Push Project to GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <repo-url>
git push -u origin main
```

---

## Work on New Feature

```bash
git switch -c feature-login
```

---

## Summary

* Real scenarios = real learning
* Mistakes are normal
* Git always allows recovery

---

💡 Practice these to gain confidence.
