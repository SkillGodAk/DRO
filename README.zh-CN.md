# DRO — 抖音播放优化工具

[繁體中文](README.md) | **简体中文** | [English](README_EN.md)

DRO 提供独立的 **Chrome 网页版扩展（0.7.5）** 与 **Windows 桌面版（20260921 打包）**。公开仓库只提供产品介绍和成品下载，不公开开发工作区与独立源码文件。

## 下载

[GitHub Releases](https://github.com/SkillGodAk/DRO/releases)

- `DRO_Web_Playback_0.7.5.zip`：Chrome 116+；适用于 www.douyin.com 与 live.douyin.com。
- `DRO_Desktop_20260921.zip`：Windows 抖音桌面程序。

## 功能与安装

网页版显示播放状态、下一条就绪信息，并在卡顿时尝试播放器提供的同视频备用来源。下载解压后打开 `chrome://extensions`，启用开发者模式，选择“加载已解压的扩展程序”，指定含 `manifest.json` 的文件夹。Chrome 扩展运行必须包含 JavaScript，因此 ZIP 内相关脚本可被查看。

桌面版按节点质量进行监测和本地学习，可暂时避开不稳定节点。完整解压后运行 `DRO_Desktop/DouyinRouteOptimizer.cmd`，根据提示授权管理员权限并配置。不要单独移动 EXE。

无法保证所有网络环境零卡顿。文件校验请查看 [SHA256SUMS](SHA256SUMS)，版本说明见 [RELEASE_NOTES.md](RELEASE_NOTES.md)。

## 赞助作者

[Buy Me a Coffee](https://buymeacoffee.com/SkillGodAK)

银行收款：<br><img src="assets/donate-bank.jpg" width="300" alt="银行收款">

微信收款：<br><img src="assets/donate-wechat.jpg" width="300" alt="微信收款">

DRO 为独立第三方工具，并非抖音或字节跳动官方产品。