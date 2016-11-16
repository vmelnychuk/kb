## Git

### Change remote from HTTPS to SSH
```shell
git remote -v # check you origin first, _tip:_ backup this value
git remote set-url origin <ssh-git-url> # change url
git remote -v # check for changes
```
### Add SSH-key to github
- `xclip -sel clip < ~/.ssh/id_rsa.pub` # copy your ssh-key to clipboard
- paste key to github
- (optional) change repo origin from HTTPS to SSH


### Merge conflict
- Step 1: Fetch the changes (saving the target branch as FETCH_HEAD).
`git fetch origin master`
- Step 2: Checkout the source branch and merge in the changes from the target branch. Resolve conflicts.
`git checkout feature/branch-with-killer-feature`
`git merge FETCH_HEAD`
- Step 3: After the merge conflicts are resolved, stage the changes accordingly, commit the changes and push.
`git commit`
`git push origin HEAD`
- Step 4: Merge the updated pull request.

### Push local branch to remote
```shell
git checkout -b <branch>
git push -u origin <branch>
```

### Revert local changes
```shell
git checkout -- .
```
but not like this:
```shell
git stash
git stash drop
```
