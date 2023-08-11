# 10 Tips and Tricks
## Add object notes
### git notes add -m 'Note on the previous commit....'
----------
## Checkout a new branch without any history
### git checkout --orphan <branch_name>
----------
## Clone a single branch
### git clone -b <branch-name> --single-branch https://github.com/user/repo.git
---------
## Create and switch new branch
### git checkout -b <branch-name>
---------
## Show inline word diff.
### git diff --word-diff
----------
## Create new working tree from HEAD state
### git worktree add --detach <path> HEAD
----------
## store deleted file.
### git checkout <deleting_commit> -- <file_path>
----------

## Clean the files from .gitignore.
### git clean -X -f
-----------
## Rename a branch
### git branch -m <new-branch-name>
-----------
## Rebases 'feature' to 'master' and merges it in to master
### git rebase master feature && git checkout master && git merge -
