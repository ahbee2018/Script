# 常用脚本集合
## (1)DD
1. MoeClub
```
bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/MoeClub/Note/master/InstallNET.sh') -d 11 -v 64 -p 密码 -port 端口 -a -firmware
```

```
-firmware  #额外的驱动支持，部分VPS不支持该参数，如甲骨文永久免费VPS
-d  #Debian系统，后面是系统版本号，如 -d 11
-c  #Centos系统，后面是系统版本号，如 -c 7
-u  #Ubuntu系统，后面是系统版本号，如 -u 22.04
-v  #后面写64或32，选择64位/32位操作系统
-a  #Auto，全自动无人值守安装
--mirror  #自定义镜像源地址
-p  #自定义密码
–ip-addr  #自定义IP地址，如：123.45.xxx.xxx （事先 ifconfig -a 获取）
–ip-gate  #自定义网关地址，如：123.45.xxx.xxx （事先 route -n 获取）
–ip-mask  #自定义掩码地址，如：255.255.xxx.xx
```

2. 秋水逸冰
https://teddysun.com/category/tech

## (2)Linux更换内核
https://github.com/ylx2016/Linux-NetSpeed

## (3)Proxy
1. 一键安装 MTProxy 代理<br>
https://github.com/ellermister/mtproxy

2. V2ray/Xray多用户管理脚本<br>
https://github.com/Jrohy/multi-v2ray


## (4)转发
1. nftables<br>
https://github.com/arloor/nftables-nat-rust

## (7)其他
1. 香港地址解析器<br>
https://g0vhk-io.github.io/HKAddressParser/#/

2. Aria2-AriaNg-X<br>
https://github.com/wahyd4/aria2-ariang-x-docker-compose

3. 独角数卡<br>
https://github.com/assimon/dujiaoka