feat: added new functionality
fix:
docs:
refactor :
test:
perf:

## Branches -

main/master - default branch

list all branches - git branch
create a new branch -

Step 1 - create a branch - git branch <branchname>,git branch <branchname> <source-branch>
Step 2 - Switch to branch - git checkout <branchname>

Step 1 and step 2 can be done in single step - git checkout -b <branch-name>
git checkout -b <branch-name> <source-branch>

### Modern way to creating branches

git switch <branchname> <source-branch> - to create a branch

git switch -c <branchname>,git switch -c <branchname> <source-branch> - to create a branch and switch to new branch

## workTreaa

git worktree add <location => <branch>
git worktree ./checkout dev
git worktree add -b <new-branch> <location> <existing-branch>
git worktree add -b feature/checkout ./checkout dev
git worktree remove checkout
git worktree list

## git reset and git revert

# adding demo content in a file

git log --oneline

to come out of vim -
escape :wq
