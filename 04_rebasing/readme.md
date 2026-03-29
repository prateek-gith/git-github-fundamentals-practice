# Git Rebase

Rebase is used to move commits from one branch to another.

---

## Rebase Command

```bash
git rebase main
```

---

## Why Use Rebase?

* Clean history
* Linear commits

---

## Rebase vs Merge

* Merge → keeps history
* Rebase → rewrites history

---

## Resolve Conflicts

```bash
git add .
git rebase --continue
```

---

## Important Note

⚠️ Do not use rebase on shared branches like main.

---

## Summary

* Rebase = clean history
* Use on feature branches
* Avoid on public branches

---

💡 Use carefully.
