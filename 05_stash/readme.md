# Git Stash

Git stash saves your uncommitted changes temporarily.

---

## Save Changes

```bash
git stash
```

With message:

```bash
git stash push -m "work"
```

---

## View Stash

```bash
git stash list
```

---

## Apply Stash

```bash
git stash apply
```

---

## Apply and Remove

```bash
git stash pop
```

---

## Delete Stash

```bash
git stash drop
```

---

## Clear All

```bash
git stash clear
```

---

## Use Case

* Switch branch without committing
* Save temporary work

---

## Summary

* Stash = temporary storage
* Helps manage unfinished work

---

💡 Use stash before switching branches.
