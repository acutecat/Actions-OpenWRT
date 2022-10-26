## Actions-OpenWRT
 使用Actions来编译路由器固件

## 关于这个固件

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/acutecat/Actions-OpenWRT/blob/main/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/acutecat/Actions-OpenWRT.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/acutecat/Actions-OpenWRT.svg?style=flat-square&label=Forks&logo=github)

> 这个仓库基于[P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)

> 用Github Actions为K2P自动编译固件

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
