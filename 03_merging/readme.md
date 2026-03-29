# Git Merging

Merging is used to combine code from one branch into another.

---

## Merge Command

```bash
git switch main
git merge feature-branch
```

---

## Types of Merge

### Fast-Forward

* No conflicts
* Simple update

---

### 3-Way Merge

* Branches are different
* Creates merge commit
* May cause conflicts

---

## Merge Conflict Example

```text
<<<<<<< HEAD
Your code
=======
Other code
>>>>>>> feature-branch
```

---

## Resolve Conflict

Steps:

1. Edit file manually
2. Remove conflict markers
3. Add file

```bash
git add file
git commit
```

---

## Summary

* Merge = combine code
* Fast-forward = simple
* 3-way = complex
* Conflicts need manual fix

---

💡 Use VS Code for easy conflict resolution.
