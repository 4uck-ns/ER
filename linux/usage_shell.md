# common

## 收集信息
cat /proc/version

## pidof
pidof /usr/bin/* | xargs kill -9

## netstat
netstat -nat|grep -i "80"|wc -l