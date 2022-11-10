## Actions-OpenWRT
 使用Actions来编译路由器固件

## 关于这个固件

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/acutecat/Actions-OpenWRT/blob/main/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/acutecat/Actions-OpenWRT.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/acutecat/Actions-OpenWRT.svg?style=flat-square&label=Forks&logo=github)

> 这个仓库基于[P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)

> 用Github Actions为K2P自动编译固件

[OpenWrt DIY — 多设备固件云编译](https://jq.qq.com/?_wv=1027&k=8uPHfZZY)
==============================================================================================================
[![若部分图片无法正常显示，请挂上机场浏览或点这里到末尾看修复教程](https://visitor-badge.glitch.me/badge?page_id=Actions-OpenWRT)](#解决-github-网页上图片显示失败的问题) [![](https://img.shields.io/github/last-commit/coolsnowwolf/lede/master?color=FFFFFF&label=%E6%BA%90%E7%A0%81%E6%9B%B4%E6%96%B0)](https://github.com/coolsnowwolf/lede) [![](https://img.shields.io/github/release-date/IvanSolis1989/OpenWrt-DIY?color=FFFFFF&label=%E5%9B%BA%E4%BB%B6%E6%9B%B4%E6%96%B0)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) [![](https://img.shields.io/badge/QQ群-点击加入-FFFFFF.svg)](https://jq.qq.com/?_wv=1027&k=8uPHfZZY)<br/>
[![](https://img.shields.io/badge/-主要功能:-696969.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/wiki/OpenWrt-DIY%E6%8F%92%E4%BB%B6%E9%A2%84%E8%A7%88) ![](https://img.shields.io/badge/-SSR_Plus+-FFFFFF.svg) ![](https://img.shields.io/badge/-PassWall-FFFFFF.svg) ![](https://img.shields.io/badge/-OpenClash-FFFFFF.svg) ![](https://img.shields.io/badge/-AdGuard_Home-FFFFFF.svg) ![](https://img.shields.io/badge/-广告屏蔽大师_Plus+-FFFFFF.svg) ![](https://img.shields.io/badge/-Samba-FFFFFF.svg) ![](https://img.shields.io/badge/-CIFSD-FFFFFF.svg) ![](https://img.shields.io/badge/-FTP-FFFFFF.svg) ![](https://img.shields.io/badge/-SFTP-FFFFFF.svg) ![](https://img.shields.io/badge/-NFS-FFFFFF.svg) ![](https://img.shields.io/badge/-DLNA-FFFFFF.svg) ![](https://img.shields.io/badge/-Aria2-FFFFFF.svg) ![](https://img.shields.io/badge/-Transmission-FFFFFF.svg) ![](https://img.shields.io/badge/-qBittorrent-FFFFFF.svg) ![](https://img.shields.io/badge/-AirPlay2-FFFFFF.svg) ![](https://img.shields.io/badge/-解锁网易云灰色歌曲-FFFFFF.svg) ![](https://img.shields.io/badge/-UPnP-FFFFFF.svg) ![](https://img.shields.io/badge/-京东签到服务-FFFFFF.svg) ![](https://img.shields.io/badge/-IPv6_加速-FFFFFF.svg) ![](https://img.shields.io/badge/-BBR_加速-FFFFFF.svg) ![](https://img.shields.io/badge/-FullCone_NAT_加速-FFFFFF.svg) ![](https://img.shields.io/badge/-SFE_加速-FFFFFF.svg) ![](https://img.shields.io/badge/-HWNAT_加速-FFFFFF.svg) ![](https://img.shields.io/badge/-桥接加速-FFFFFF.svg) ![](https://img.shields.io/badge/-DDNS-FFFFFF.svg) ![](https://img.shields.io/badge/-Docker_容器-FFFFFF.svg) ![](https://img.shields.io/badge/-ARP_绑定-FFFFFF.svg) ![](https://img.shields.io/badge/-Frpc_NPS_内网穿透-FFFFFF.svg) ![](https://img.shields.io/badge/-多线多拨-FFFFFF.svg) ![](https://img.shields.io/badge/-负载均衡-FFFFFF.svg) ![](https://img.shields.io/badge/-SQM_Qos-FFFFFF.svg) ![](https://img.shields.io/badge/-文件助手-FFFFFF.svg) ![](https://img.shields.io/badge/-文件浏览器-FFFFFF.svg) ![](https://img.shields.io/badge/-可道云-FFFFFF.svg) ![](https://img.shields.io/badge/-Rclone-FFFFFF.svg) ![](https://img.shields.io/badge/-SmartDNS-FFFFFF.svg) ![](https://img.shields.io/badge/-网络唤醒-FFFFFF.svg) ![](https://img.shields.io/badge/-TTYD_终端-FFFFFF.svg) ![](https://img.shields.io/badge/-迅雷快鸟-FFFFFF.svg) ![](https://img.shields.io/badge/-USB_打印服务器-FFFFFF.svg) ![](https://img.shields.io/badge/-KMS_服务器-FFFFFF.svg) ![](https://img.shields.io/badge/-微信推送-FFFFFF.svg) ![](https://img.shields.io/badge/-上网时间控制-FFFFFF.svg) ![](https://img.shields.io/badge/-WatchCat-FFFFFF.svg) ![](https://img.shields.io/badge/-天翼家庭云盘提速-FFFFFF.svg) ![](https://img.shields.io/badge/-各种驱动-FFFFFF.svg) ![](https://img.shields.io/badge/-DNS_Filter-FFFFFF.svg) ![](https://img.shields.io/badge/-持续更新中……-FFFFFF.svg)
 ==============================================================================================================
 [![](https://img.shields.io/badge/-目录:-696969.svg)](#readme) [![](https://img.shields.io/badge/-固件下载-FFFFFF.svg)](#固件下载-) [![](https://img.shields.io/badge/-基本介绍-FFFFFF.svg)](#基本介绍-) [![](https://img.shields.io/badge/-近期更新-FFFFFF.svg)](#近期更新-) [![](https://img.shields.io/badge/-注意事项-FFFFFF.svg)](#注意事项-) [![](https://img.shields.io/badge/-小贴士-FFFFFF.svg)](#小贴士-) [![](https://img.shields.io/badge/-捐助-FFFFFF.svg)](#捐助-) [![](https://img.shields.io/badge/-鸣谢-FFFFFF.svg)](#鸣谢-)

请 `耐心认真阅读完毕` 本页面，本页面包含如何提升固件下载及使用体验的内容。

如果您未阅读完本页面，可能会遇到 `固件下载问题` ，若遇到问题，请 `返回此页面，认真完整阅读一遍`~

## 固件下载 [![](https://img.shields.io/badge/-支持设备、编译状态及固件下载-FFFFFF.svg)](#固件下载-)
<details>
 <summary><b>&nbsp;&nbsp;&nbsp; X86  设备编译状态及固件下载</b></summary>
    
<br/>

点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 即可跳转到该设备固件下载页面
|   序号    |     X86设备  |   X86设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 
| 1 |   [![](https://img.shields.io/badge/Build-x86_64-FFFFFF.svg)](https://github.com/acutecat/Actions-OpenWRT/blob/main/.github/workflows/Build-x86_64.yml)    | [![](https://github.com/acutecat/Actions-OpenWRT/workflows/Build-x86_64/badge.svg)](https://github.com/acutecat/Actions-OpenWRT/actions/workflows/Build-x86_64.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/acutecat/Actions-OpenWRT/blob/main/x86_64/x86_64.config) |  |  

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/acutecat/Actions-OpenWRT/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/acutecat/Actions-OpenWRT/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/acutecat/Actions-OpenWRT/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/acutecat/Actions-OpenWRT/actions) 到 **Actions** 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; ARM 设备编译状态及固件下载</b></summary>
    
<br/>

点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 即可跳转到该设备固件下载页面
|    序号   |     ARM设备    |   ARM设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 到 Actions 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; 高通 设备编译状态及固件下载</b></summary>
    
<br/>

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 到 Actions 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; MIPS 设备编译状态及固件下载</b></summary>
    
<br/>

**注意：** 考虑到 MIPS 设备的 CPU 性能及 RAM/ROM 量配置，功能较其他设备做了很大范围的删减。 

MIPS 设备推荐使用 Padavan 固件： [![](https://img.shields.io/badge/-Padavan_固件仓库_1-FFFFFF.svg)](https://github.com/hanwckf/rt-n56u) [![](https://img.shields.io/badge/-Padavan_固件仓库_2-FFFFFF.svg)](https://opt.cn2qq.com/padavan/) [![](https://img.shields.io/badge/-Padavan_固件仓库_3-FFFFFF.svg)](https://github.com/gorden5566/padavan)

点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 即可跳转到该设备固件下载页面
|    序号   |     MIPS设备     |   MIPS设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/IvanSolis1989/OpenWrt-DIY/actions) 到 Actions 进一步查看。

</details>

## 小贴士 [![](https://img.shields.io/badge/-日常使用技巧及教程-FFFFFF.svg)](#小贴士-)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 本栏目包含了很多 OpenWrt 日常使用问题解决方案、“不可描述”的教程、广告屏蔽教程，NAS（或路由器共享盘）的多媒体文件整理播放教程、OpenWrt 本地自编译教程。

<details>
 <summary>&nbsp;&nbsp;&nbsp; 不可描述</summary>

<br/>

[最好的 OpenWrt 路由器 shadowsocks 自动翻墙、科学上网教程](https://github.com/softwaredownload/openwrt-fanqiang)

[自由上网方法大全](https://github.com/Alvin9999/new-pac/wiki)

[Clash for Windows](https://github.com/Fndroid/clash_for_windows_pkg)

[WinXray](https://github.com/TheMRLL/winxray)

[翻墙软件 VPN 推荐指南（含 2020 优惠）](https://github.com/vpncn/vpncn.github.io)

[免费机场节点获取 1](https://github.com/hugetiny/awesome-vpn/blob/master/READMECN.md)

[免费机场节点获取 2](https://bu.link2.workers.dev/https/github.com/freefq/free)

</details>

<details>
 <summary>&nbsp;&nbsp;&nbsp; 本地编译</summary>

<br/>

[基本编译教程](https://blog.csdn.net/Dreame_Architect/article/details/101527640)

[WIN10 内置 Ubuntu 子系统编译教程](http://www.fuweijun.com/index.php/2019/07/03/win10%E5%AD%90linux%E7%B3%BB%E7%BB%9F%E7%BC%96%E8%AF%91openwrt/)

[Win10 子系统 Ubuntu18.04 下编译 OpenWrt 问题及解决方法](https://blog.csdn.net/khaunag/article/details/104854536)

[Ubuntu 默认源更新慢可更换清华大学镜像源](https://mirror.tuna.tsinghua.edu.cn/help/ubuntu/)

[Lean's OpenWrt 插件大全](https://github.com/IvanSolis1989/OpenWrt-DIY/wiki/Lean‘s-OpenWrt-——LuCI-Applications-插件说明)

</details>

## 使用方法：

- 单击[“使用此模板”](https://github.com/acutecat/Actions-OpenWRT/generate)按钮创建新的存储库。
- 生成使用[Lean's OpenWrt](https://github.com/coolsnowwolf/lede)源代码配置文件。（可以通过工作流文件中的环境变量进行更改。）
- 推将配置文件保存到GitHub存储库。
- 在操作页面上选择Build OpenWrt。
- 单击“运行工作流”按钮。
- 构建完成后，单击Actions页面右上角的Artifacts按钮下载二进制文件。

## 注意：

- 可能需要很长时间才能创建 `.config` 文件并构建OpenWrt固件。因此，在创建存储库来构建自己的固件之前，您可以通过在GitHub中搜索[`Actions-Openwrt`](https://github.com/search?q=Actions-openwrt)来查看其他人是否已经构建了满足您需求的固件。 
-在存储库简介中添加一些构建固件的元信息（例如固件体系结构和安装的软件包），这将节省其他人的时间。

## 致谢名单:

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)
- [P3TERX](https://github.com/P3TERX/Actions-OpenWrt)

## 许可证

[MIT](https://github.com/acutecat/Actions-OpenWRT/blob/main/LICENSE) © [**Acutecat**](https://github.com/acutecat/Actions-OpenWRT/blob/main/LICENSE)
 & [**P3TERX**](https://p3terx.com)
