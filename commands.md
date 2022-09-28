# Initialize a repository for Graphite

> Graphite stores metadata in `.git` about your stacks

```
gt init
```

---

# Make some changes and create a stack

```
git add .
gt branch create <branch>
```

---

# Create a PR

```
gt stack submit
```

---

# Create three more stacks

---

# View stacks

```
gt log
```

---

# Move a stack onto a new parent

```
gt upstack onto
```

---

# Create a stack with more than one commit

---

# Combine two stacks into one stack with two commits

```
gt branch split
```

---

# Split one stack with two commits into two stacks

```
gt branch fold
```

---

# Amend a stack that has children

```
git commit --amend
```

---

# Rebase stacks onto updated parent

```
gt upstack restack
```

---

# Create PRs

```
gt stack submit
```

---

# Merge in a PR

---

# Update Repo and update stacks and PRs

```
gt repo sync
gt upstack restack
gt stack submit
```

---

# All done!

