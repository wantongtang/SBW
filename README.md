#CentOS 服务器一键安装/配置模板教程
###阿里云/腾讯云SQ防扫升级
###服务系统：CentOS 6.x 64位 (支持蜂巢Centos 6.7)
###推荐宽带：10M 以上
###更新时间：2016-04-23 （新增常规VPS Centos7.0）
###重启服务：vpn （仅支持此命令重启服务）
###常规VPS脚本：适用于腾讯云、阿里云等正规VPS使用，内置SQ防扫验证，高效稳定，支持开机自启 
###网易蜂巢脚本：适用于网易蜂巢CentOS6.7容器服务，完美适配容器环境，不支持开机自启 
###Centos7.0脚本：仅适用于腾讯云、阿里云CentOS7.0使用，支持全国大部分地区移动/联通用户免流

1) 使用 root 账号登录 Linux 服务器。

2）执行一键安装脚本：

授权码： 授权码：0668 

常规VPS安装脚本（已修复启动问题）：

wget http://sbwml.cn/openvpn && bash openvpn

网易蜂巢安装脚本：

wget http://sbwml.cn/vpn163 && bash vpn163

阿里云/腾讯云Centos7.0 （支持http代理转接）：
代码加密，暂不支持蜂巢服务器

wget http://sbwml.cn/vpnhttp && bash vpnhttp

如果提示出错 bash: wget: command not found 请执行 yum install -y wget

3) 根据终端返回提示完成安装配置。

4) 安装完成后，复制终端输出的地址并下载链接中的配置文件。


5) 解压下载的压缩包，提取OpenVPN.ovpn。

CA证书：ca.crt
TLS密钥：ta.key
成品配置文件：OpenVPN.ovpn

应用OpenVPN配置到iPhone
马上迈向成功的喜悦。

:)


##安装OpenVPN程序
Apple ID：1335538902@qq.com
密码：Aa20162016

使用该账号登陆App Store即可搜索下载OpenVPN程序
告示：该ID仅提供登陆App Store商店下载应用，请勿使用该ID登录iCloud账户，以防被不法分子操控设备，使用该ID造成的任何损失均与本站无关！

链接OpenVPN
把OpenVPN.ovpn文件发送到QQ/其他应用，并使用其他程序打开（OpenVPN程序）
OpenVPN 内点击添加新配置文件，并链接VPN。


##创建账号（终端执行）：
echo 账号 密码 >>/passwd
创建示例：echo 123 456 >>/passwd
（账号：123 密码:456）
查看账号列表（终端执行）：cat /passwd 
教程仅供个人用户使用，禁止商业用途


内置移动4G 模式，尽情测试去吧！
免流代码在OpenVPN.ovpn文件内，可自行进行修改！

#other

wget http://www.moli52.com/vpn/tgopenvpn.sh; bash tgopenvpn.sh


