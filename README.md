# NetSpeed
   ———Tomy
   
更新bbr及bbrplus内核为最新版（不含centos6及32位系统）
#bbr魔改版可能无法使用

一键使用：
github版
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/Starktomy/NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```
cloudflare版（适合国内及其他无法访问github机器）
```
wget -N --no-check-certificate "https://netspeed.fucku.workers.dev/tcp-cf.sh?a=view"
chmod +x tcp-cf.sh
./tcp-cf.sh
```
查看当前运行的算法 cat /proc/sys/net/ipv4/tcp_congestion_control

bbr内核由本人自编译

bbrplus内核由@ylx2016大佬编译https://github.com/ylx2016/kernel

