# SmartDNS-script
用于便捷安装、检测和卸载[SmartDNS-rs](https://github.com/mokeyish/smartdns-rs) （即windows版SmartDNS）的脚本。
其中，service-install表示重新安装SmartDNS-rs的服务，即无论是否已经安装服务，都会重新安装一次；service-install表示卸载服务，并刷新系统DNS缓存；service-restart则表示重启服务，并刷新系统DNS缓存。“检测”则表示使用nslookup命令检测SmartDNS是否生效。

