如果你派生(Fork)本项目，请通过如下地址提交一个 PR：
https://github.com/NeverMin/smarthosts/pulls

在墙内通过 TCP 方式查询 DNS(但不能用墙内的DNS)，例如：
dig +tcp @8.8.8.8 wwww.google.com

如果你需要 dig 工具，Windows 用户可以安装 BIND9：
http://www.isc.org/downloads/

Linux 用户安装 bind9utils 即可。

注：YouTube的视频无法加载，但视频页可以打开。 

SmartHosts不会在Hosts中加入来路不明的IP，所有IP都处于官方服务器所使用的IP段中。
某些网站需要您使用https方式打开，例如:

Facebook: https://www.facebook.com 
