## 无法与Windows主机通信问题 {#windows}

主机间通信需要使用SSH服务，Linux主机自带SSH服务，而windows主机没有该服务，因此用户必须在windows主机上安装winSSHD.exe和wget.exe才能实现Linux与windows主机间的通信。

操作步骤：

*   1.安装WinSSHD5-Inst.exe服务并启动。
*   2.将wget.exe文件拷贝到环境变量目录（如C:\Windows\System32）下。