# Git Commands

## 1. Initialization
- **Create a new Git repository**:
  
  `git init`

## 2. Configuration
- **Set global username**:
  
  `git config --global user.name "rahulfulpgare"`

- **Set global email**:
  
  `git config --global user.email "rahulfulpgare@gmail.com"`
  
- **Edit global Git configuration**:
  
  `git config --global --edit`

  This opens your global Git configuration file (usually `~/.gitconfig`) in your default editor, allowing you to manually edit settings.
  
## 3. File Operations
- **Create a new file**:
  
  `touch <filename>`

- **Remove a file**:
  
  `rm <filename>`

- **Restore a deleted file**:
  
  `git restore <filename>`

## 4. Staging and Commit
- **Check the status of the repository**:
  
  `git status`

- **Add a file to the staging area**:
  
  `git add <filename>`

- **Commit changes with a message**:
  
  `git commit -m "your commit message"`

## 5. Cloning a Repository
- **Clone an existing repository**:
  
  `git clone <repository_url>`

## 6. Branching
- **Create a new branch**:
  
  `git checkout -b <branch_name>`

- **Switch between branches**:
  
  `git checkout <branch_name>`
  
  `git switch <branch_name>`

- **List all branches**:
  
  `git branch`

- **Delete a branch locally**:
  
  `git branch -d <branch_name>`

- **Force delete a branch locally (if it has unmerged changes)**:
  
  `git branch -D <branch_name>`

- **Delete a branch remotely**:
  
  `git push origin --delete <branch_name>`

## 7. Logs and Diffs
- **View commit history**:
  
  `git log`

- **View concise commit history**:
  
  `git log --oneline`

- **View changes between working directory and the index (staging area)**:
  
  `git diff`

- **View changes between last commit and the working directory**:
  
  `git diff HEAD`

- **Show detailed information about a specific commit**:
  
  `git show <commit_id>`

## 8. Resetting and Reverting
- **Unstage a file (remove from index but keep in working directory)**:
  
  `git rm --cached <filename>`

- **Reset changes in staging area (move to working directory)**:
  
  `git reset <filename>`

- **Reset to a specific commit but keep changes in working directory**:
  
  `git reset <commit_id>`

- **Hard reset to a specific commit (discard all changes, both in staging and working directory)**:
  
  `git reset --hard <commit_id>`

## 9. Sync with Remote Repository
- **Push changes to remote repository**:
  
  `git push origin <branch_name>`

- **Pull updates from remote repository**:
  
  `git pull origin <branch_name>`

- **Merge changes from another branch**:
  
  `git merge <branch_name>`

- **Fetch latest updates from remote (does not merge)**:
  
  `git fetch origin <branch_name>`

- **Sync a forked repository with the original (upstream)**:
  
  1. **Add the upstream remote**:
     
     `git remote add upstream <original_repo_url>`

  2. **Fetch the latest changes from upstream**:
     
     `git fetch upstream`

  3. **Merge upstream changes into your local fork**:
     
     `git merge upstream/<branch_name>`

  4. **Push changes to your fork**:
     
     `git push origin <branch_name>`

## 10. Miscellaneous
- **View all files, including hidden ones**:
  
  `ls -a`

- **Clear terminal screen**:
  
  `clear`

- **View command history**:
  
  `history`
