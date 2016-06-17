## Agent无法正常注册 {#agent}

*   请确保注册agent的主机防火墙是关闭的。
*   有可能您的主机没有主机名（hostname），请先配置。
*   确保主机有远程登录、下载和解压等命令所需命令的具体列表如下：ssh（默认端口22），wget，gem，gcc, make, yum, unzip ,killall, netstat,Iostat。（注：以上命令必须已安装并已启动）