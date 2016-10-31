## Git

### Change remote from HTTPS to SSH
```shell
git remote -v # check you origin first, _tip:_ backup this value
git remote set-url origin <ssh-git-url> # change url
git remote -v # check for changes
```
### Add SSH-key to github
- ```shell
xclip -sel clip < ~/.ssh/id_rsa.pub # copy your ssh-key to clipboard
```
- paste key to github
- (optional) change repo origin from HTTPS to SSH
