## Show which port used by application
```shell
jps -l
lsof -p <PID> -a -i
lsof -Pan -p <PID> -i
```
