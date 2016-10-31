## SSH

### Generate SSH keys and put them to remote server
```shell
ssh-keygen -b 4096 -t rsa -C "vasyl.melnychuk@4finance.com" # generate RSA key with comment and size 4096
ssh-keygen -lf /path/to/id_rsa.pub # show fingerprint,size,comment of public key
```
