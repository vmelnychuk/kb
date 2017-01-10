## Ubuntu tasks and tips

#### Istall package from _deb_ file 
```shell
sudo dpkg -i 
sudo apt-get install -f
```


#### Remove installed package
```shell
sudo apt remove --auto-remove virtualbox-5.1 # delete depes, keep configs
sudo apt-get purge --auto-remove virtualbox # delete deps, delete configs
```
