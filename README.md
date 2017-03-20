# commons-container
Aliases etc. 

## .bashrc
```
# Git alias
alias gs="git status"
alias ga="git add"
alias glog="git log"
alias gcm="git commit -m"
alias gd="git diff"

# Mongodb alias
alias startmongodb="sudo service mongod start"
alias stopmongodb="sudo service mongod stop"
alias restartmongodb="sudo service mongod restart"

# Find stuff
alias greplinesrec="grep -rin "



```

## connect raspi
```
# fixed ip
dwc_otg.lpm_enable=0 console=ttyAMA0,115200 console=tty1 root=/dev/mmcblk0p2 rootfstype=ext4 ip=169.254.182.11 elevator=deadline rootwait

# dhcp (?)
dwc_otg.lpm_enable=0 console=ttyAMA0,115200 console=tty1 root=/dev/mmcblk0p2 rootfstype=ext4 ip=10.0.1.201 elevator=deadline rootwait

# use nmap to find hosts in network (http://askubuntu.com/questions/425907/nmap-in-ubuntu-13-10)
nmap -sn -oG ip.txt 10.0.1.1-255

# use arp
arp -a

```
