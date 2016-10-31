## Git

### Change remote from HTTPS to SSH
```shell
git remote -v # check you origin first, _tip:_ backup this value
git remote set-url origin <ssh-git-url> # change url
git remote -v # check for changes
```
