http://stackoverflow.com/questions/3855127/find-and-kill-process-locking-port-3000-on-mac

```
netstat -anp tcp | grep 3000

lsof -i tcp:3000
```