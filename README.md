<div align="center">
<h1>OpenWrt-Mini  急速精简科学版，云编译更新</h1>
</div>

## 固件说明：
 - 采用 Linux 6.1 LTS 最新稳定版内核，纯净精简，高效稳定
 - 仅安装科学上网必要插件，剔除多余功能，提供旁路由轻量版本
 - 集成snmp，keepalived插件，支持集群功能（无Gui管理）
 - 科学插件集成有：ShadowSocksR Plus+  PassWall  PassWall2  OpenClash
 - 插件：[ShadowSocksR Plus+](https://github.com/fw876/helloworld.git)、[PassWall](https://github.com/xiaorouji/openwrt-passwall.git)、[OpenClash](https://github.com/vernesong/OpenClash.git)
 - 插件：[luci-app-easytier](https://github.com/iii80/luci-app-easytier/releases/download/untagged-4939479d22893e21b4f8/luci-app-easytier_all.ipk)、[EasyTier](https://github.com/EasyTier/EasyTier/releases)、[Lucky](https://github.com/gdy666/luci-app-lucky/releases)
 - easytier 依赖kmod-tun``luci-lib-fs需要先在系统软件包里安装好
   
| 管理地址  | 默认账号 | 默认密码 |
| ---- | ---- | ---- |
| 192.168.0.111 | root | 无密码 |

## 固件下载:   [Releases](https://github.com/iii80/My-lede/releases) 

目前支持x86主机，其他常用机型待添加

精力有限，目前只支持自己的常用设备

注：

1、OpenWrt-R23.7.7-内核5.15自用版 为最新lean代码R23.7.7默认5.15内核集成科学插件版本

2、OpenWrt-R23.7.7-内核6.1自用版 为最新lean代码R23.7.7默认6.1内核集成科学插件版本
