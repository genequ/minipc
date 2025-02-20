最近京东入手了一个小主机 https://item.jd.com/10059957371928.html

## 基本配置如下：
* CPU：N5105
* RAM：8 GB
* SSD：256 GB

机器开箱时已经安装了Windows 10，顺利升级到了 Windows 11，运行还算流畅。
运行功率10W，非常适合常年开机在上面跑一些服务。后续准备把跑在树莓派3上的服务迁移过来。

## 服务 & 软件

* Transmission https://github.com/transmission/transmission/releases
  - Demon 配置：C:\Windows\ServiceProfiles\LocalService\AppData\Local\transmission-daemon
  - \\\\wdmycloud\\transmission
  - Web: http://minipc:9091/transmission/web
* Docker
  - TeslaMate
  - Aliyun WebDav
* Jellyfin https://github.com/jellyfin/jellyfin
  - Web: http://minipc:8096/web/index.html#!/home.html
  - 插件：https://github.com/cxfksword/jellyfin-plugin-metashark 
* Tailscale
