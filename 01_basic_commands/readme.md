# Basic Git Commands

This section covers the most important Git commands that every developer should know.

---

## Initialize Repository

```bash
git init
```

Creates a new Git repository and starts tracking the project.

---

## Check Repository Status

```bash
git status
```

Shows current state of files:

* Tracked
* Untracked
* Staged

---

## Add Files

Add specific files:

```bash
git add file1 file2
```

Add all files:

```bash
git add .
```

---

## Commit Changes

```bash
git commit -m "Your message"
```

Creates a checkpoint (snapshot) of your code.

---

## View History

```bash
git log
```

Short version:

```bash
git log --oneline
```

---

## Git Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

---

## Summary

* git init → start repo
* git add → stage changes
* git commit → save changes
* git status → check state
* git log → history

---

💡 These are the foundation commands of Git.
