# v2ray
最好用的 V2Ray 一键安装脚本 &amp; 管理脚本

安装或卸载
要求：Ubuntu 14+ / Debian 7+ / CentOS 7+ 系统的小鸡鸡
推荐使用 Debian 9 系统，脚本会自动启用 BBR 优化。
使用 root 用户输入下面命令安装或卸载

bash <(curl -s -L https://github.com/gmlian/v2ray/v2ray.sh)
如果提示 curl: command not found ，那是因为你的小鸡没装 Curl
ubuntu/debian 系统安装 Curl 方法: apt-get update -y && apt-get install curl -y
centos 系统安装 Curl 方法: yum update -y && yum install curl -y
安装好 curl 之后就能安装脚本了

注意事项：如果你是 CentOS 7 系统，此脚本会关闭 firewalld 并且使用 iptables
备注：安装完成后，输入 v2ray 即可管理 V2Ray
如果提示你的系统不支持此脚本，那么请尝试更换系统
