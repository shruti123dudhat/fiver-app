# Demo

This is a demo.

## Author

Shruti Dudhat123

## Git Commands

- `ls -a`: Check all files (hidden and unhidden).
- `git status`: Check status.
- `git add .`: Add all changes to Git.
- `git commit -m "demo"`: Commit with a message (it is a record of change).
- `git push origin main`: Push your code to GitHub.
- `git log`: See all commits.

## Creating a New Project

- `mkdir myproject`  : Create a new directory
- `cd myproject`     : Navigate into the new directory
- `git init`         : Initialize a new Git repository
- `git remote add origin <link>`   : Add the remote repository (click on the green button to get the link)
- `git remote -v`     : Verify remote
- `git branch`        : Check branch
- `git branch -M main`: Rename branch
- `git push origin main`: Push your code to GitHub

## Add new file in existing project
- `git status`
- `git add <filename or foldername>`
- `git commit -m "<Your_message>"`
- `git push origin main`

## Branch commands
- `git branch`
- `git checkout <branch name>` (to navigate)
- `git branch -M main` (to rename branch)
- `git checkout -b <new branch name>` (to create a new branch)
- `git branch -d <branch name>` (to delete branch)

## Merge Code

- `git diff <branch name>` (to compare commits, branches, files, and more)
- `git merge <branch name>` (to merge two branches)

## Rebase Code

- `git checkout <branch name>`(switch branch)
- `git rebase <branch name>` (Start the rebase)
- `git merge <branch name>` (to merge two branches)
- `git rebase --continue` (continue rebase)
- `git rebase --abort` (stop rebase)

## Pull Request (PR)

- Click "compare and pull request"
- Add title
- Create pull request

## Pull Request (PR) Workflow

- The senior developer checks the code, and if any issues are found, they add comments.
- Click "Merge pull request."
- Confirm the merge.

When merging code on GitHub and also merging it into the local system:

- `git pull origin main`

## Merge conflicts
when 2 developers are working on same part of project & both have made different changes in that part then when one person try to merge his code into another's code it shows an error called.

- `git merge main`
# Undoing Changes in Git

### Undoing the Last Commit
#### Step 1: Stage Changes

```bash
git reset <file name>
git reset
```
### Undoing the Last one Commit
#### Step 2: commited changes

```bash
git reset HEAD~1
```
### For many commits
#### Step 3: commited changes

```bash
git reset <commit hash>
git reset --hard<commited hash>
```
## Fork
You want to create a copy of a other public repository in your GitHub account
