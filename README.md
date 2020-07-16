# 2020-07-16-CCatHome-git-dan
Carpentries at Home 2020

- `git clone <url>`: download the repo from the web to your computer
    - make sure you are not in another repo
    - just like `git init` do only one per repo

## Branches

- `git branch <branch_name>`: creates a new branch where you are
- `git switch <branch_name>`: moves to the branch
    - `git checkout <branch_name>`: the "older" way

- shortcuts for creating branches, will create and move to them in 1 go:
    - `git checkout -b <branch_name>
    - `git swith -c <branch_name>

- `git branch -d <branch_name>`: this will delete <branch_name> on your local computer
- `git fetch --prune`: will update your local git tree with the remote
    - the prune will also delete references to branches that were deleted on the remote
