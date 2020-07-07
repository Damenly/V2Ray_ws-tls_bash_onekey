## V2Ray 基于 Nginx 的 vmess+ws+tls 一键安装脚本

基于https://github.com/wulabing/V2Ray_ws-tls_bash_onekey

Usage: wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/damenly/V2Ray_ws-tls_bash_onekey/master/install.sh" && chmod +x install.sh && bash install.sh

Changes:
    1. 不再在443部属wulabing的3DList
    2. 不再自己编译nginx，使用包管理器自带的（安装更加迅速）
    3. 不再关闭防火墙和ufw（更加安全)
    4. 不再在名称前增加"wulabing_"前缀（更加干净）



