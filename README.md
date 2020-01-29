# NetSpeed
   ———Tomy
   
更新bbr及bbrplus内核为最新版（不含centos6及32位系统）

一键使用：

```
wget -N --no-check-certificate "https://raw.githubusercontent.com/Starktomy/NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```
查看当前运行的算法 cat /proc/sys/net/ipv4/tcp_congestion_control

bbr内核由本人自编译

bbrplus内核由@ylx2016大佬编译https://github.com/ylx2016/kernel

