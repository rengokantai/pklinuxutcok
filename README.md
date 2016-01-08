#### pklinuxutcok

- cp6
to see process currently running on the system
```
ps auxw
```
to see the processes in real time run
```
top
```
view hard and soft limits on a process
```
ulimit -a
```
to see ps in tree format:
```
pstree
```
pscommand
```
ps auxw
a # ps has a tty
x # do not have atty
u # user oriented
w # wide screen option
```
top
```
top -d 1 -n 10  #update, time
-p (monitor specific pid)
-H show threads
-u username
```
