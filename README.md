# git_cheat_sheet

### Undo a Git merge that hasn't been pushed yet (https://stackoverflow.com/a/14586751)
git reset --merge ORIG_HEAD

### Merge all changes from other branch to staged area (without creating any commit) (https://stackoverflow.com/a/41772786)
git merge --no-commit --squash branch_name
