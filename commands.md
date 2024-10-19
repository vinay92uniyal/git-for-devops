
# Git Commands

## 1. **Setup and Configuration**
### Initializing and configuring a repository
```bash
# Create a new directory and initialize it as a Git repository
mkdir git-for-devops 
cd git-for-devops/
git init

# Configure Git with your global user details
git config --global user.name "your-username"
git config --global user.email "your-email@example.com"
```

---

## 2. **File Management**
### Adding and removing files from tracking
```bash
# Add files to staging area
git add nibbi.txt
git add nibba.txt

# Remove a file from the staging area
git rm --cached nibba.txt

# Delete a file from the working directory
rm nibba.txt
```

---

## 3. **Committing Changes**
### Saving changes with meaningful messages
```bash
# Commit all staged changes with a message
git commit -m "Initial commit: adding nibbi and nibba"

# Check status of the repository after committing
git status
```

---

## 4. **Branching**
### Managing branches for development
```bash
# Create a new branch named "dev"
git checkout -b dev

# Switch between branches
git checkout master
git checkout dev
```

---

## 5. **Viewing History**
### Log and show commit details
```bash
# View the commit history
git log
git log --oneline

# Show the changes made in a specific commit
git show 9123c5fcb2f85d611326783f8a0540e8b4173221
```

---

## 6. **Restoring Files**
### Restoring modified or deleted files
```bash
# Restore a specific file from the staging area
git restore nibbi.txt
```

---

## 7. **Working with Remote Repositories**
### Push and pull changes
```bash
# Push local changes to a remote repository
git push origin master

# Pull latest changes from a remote repository
git pull origin master
```

---

