## 1. Initialize a new Git repository
git init

## Clone an existing repository
git clone <repository-url>

## 2. Viewing and Navigating

## Show all files, including hidden ones
ls -a

## Check the current status of the repository
git status

## Show a list of all branches
git branch

## 3. **Working with Files**

## Add a file to the staging area
git add <filename>

## Add multiple files to the staging area
touch nibba.txt nibbi.txt

## Stage all files to the staging area
git add .

## Remove a file from the working directory
rm <filename>

## Restore a deleted file from staging
git restore <filename>

## Remove a file from the Git index (unstage)
git rm --cached <filename>


## 4. Committing Changes
## Commit staged changes with a message
git commit -m "your commit message"

## Show the commit history
git log

## Show a one-line summary of commit history
git log --oneline


## 5. Branching
## Create a new branch and switch to it
git checkout -b <branch-name>

## Switch between branches
git switch <branch-name>

## View current branches
git branch


## 6. Restoring and Undoing Changes
## Restore a file from staging
git restore <filename>

## Revert a commit (creates a new commit to undo)
git revert <commit-hash>

## 7. Adding Files to Staging Area
## Add a specific file
git add nibbi.txt

## Add multiple files
git add nibba.txt nibbi.txt

## Unstage a file without removing it
git reset <filename>

## Add all changes
git add .


## 8. Merging Changes
## Merge a branch into the current branch
git merge <branch-name>



## 9. Pushing and Pulling Changes
## Add a remote repository
git remote add origin <repository-url>

## Push changes to the remote repository
git push origin <branch-name>

## Pull changes from the remote repository
git pull origin <branch-name>



## 10. Logs and History

## Show the commit history
git log

## Show a compact version of commit history
git log --oneline


