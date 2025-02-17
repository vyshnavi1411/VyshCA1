## Git Commit States

Git tracks files through different states in the repository:

### 📝 Untracked  
- Newly created files that are not yet tracked by Git.  
- They do not appear in the staging area.

### 📌 Staged  
- Files that have been added to the **staging area** and are ready to be committed.  
- These changes will be included in the next commit.

### ✅ Committed  
- Files that have been permanently saved in the local repository.  
- They are stored in Git’s history with a unique commit ID.

## Importance of Git History in Version Control and Debugging

### 🔄 Version Control  
- Git history provides a complete record of changes made to a project over time.  
- It helps track who made changes, what was changed, and when.  
- Enables collaboration by allowing multiple developers to work on the same project efficiently.

### 🛠️ Debugging  
- Helps identify when and where a bug was introduced using `git bisect`.  
- Allows reverting to previous stable versions with `git checkout` or `git revert`.  
- Commit messages provide context for changes, making debugging easier.


