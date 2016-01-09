#### pklinuxutcok
- cp4
```
ifconfig
```
get ipv6 updereth0/wlan0, like 1111:1111:1111:1111:1111:1111:1111:1111
```
ping6 <idv6addr>
```
- cp5
delete all rules:
```
iptables -F
```
block specific ip:
```
iptables -A INPUT -s 1.1.1.1 -j DROP
```
allow loopback:
```
iptables -A INPUT -i lo -j ACCEPT
```
allow loopback:
```
iptables -A INPUT -i lo -j ACCEPT
iptables -A OUTPUT -o lo -j ACCEPT
```
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
