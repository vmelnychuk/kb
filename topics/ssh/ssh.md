## SSH

### Generate SSH keys and put them to remote server
```shell
ssh-keygen -b 4096 -t rsa -C "my-mail@gmail.com" # generate RSA key with comment and size 4096
ssh-keygen -lf /path/to/id_rsa.pub # show fingerprint,size,comment of public key
ssh-add # load key to the ssh-agent
ssh-add -L # check added key
ssh-copy-id -i <user-name@remote-host> # copy key to remote host
ssh <user-name@remote-host>
```
