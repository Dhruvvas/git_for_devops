# Git Commands and Related Topics

## 1. **Setup and Initialization**

### Commands:
```bash
# Create a new directory and navigate to it
mkdir git_for_devops
cd git_for_devops/

# Initialize a Git repository
git init
```

---

## 2. **Basic File Operations**

### Commands:
```bash
# Create new files
touch test1.txt test2.txt

# List files in the directory
ll

# Remove a file
rm test1.txt

# Print the current working directory
pwd
```

---

## 3. **Tracking Changes**

### Commands:
```bash
# Check the status of the working directory
git status

# Stage all changes
git add .

# Unstage a specific file
git rm --cached test1.txt

# Commit staged changes with a message
git commit -m "All files are committed"
```

---

## 4. **Configuration**

### Commands:
```bash
# Set the global username
git config --global user.name "dhruv"

# Set the global email
git config --global user.email "dv@hotmail.com"
```

---

## 5. **File Restoration**

### Commands:
```bash
# Restore a file to its previous state
git restore test1.txt
```

---

## 6. **Viewing Logs and History**

### Commands:
```bash
# View the commit history
git log

# View the command history (terminal-specific)
history
```

---

## 7. **Utility Commands**

### Commands:
```bash
# Clear the terminal screen
clear

# Navigate back to the project directory
cd git_for_devops/
```

---

### Notes:
- Always ensure you commit frequently to keep a clear history of changes.
- Use `git status` regularly to stay aware of your working directory state.
- Configure your Git username and email globally to avoid errors during commits.
