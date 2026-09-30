# DRO — 抖音播放优化工具

[繁體中文](README.md) | **简体中文** | [English](README_EN.md)

DRO 分为独立的 **Windows 桌面版**和 **Chrome 网页版**，两者不是同一种拦截方式。本仓库提供成品、说明与作者赞助信息，不公开私人开发工作区及独立桌面源码。

## 两个版本有什么区别？

| 项目 | 桌面版 | 网页版 |
| --- | --- | --- |
| 适用环境 | Windows 抖音客户端 | Chrome 上的 www.douyin.com／live.douyin.com |
| 优化方式 | 在系统侧观察节点与连接质量，通过网络过滤暂时屏蔽不良节点 | 观察网页播放器状态，在卡顿时尝试页面已提供的同一视频备用来源 |
| 限制 | 需要管理员权限才能控制相关系统功能 | 受浏览器及网站播放器限制，无法像桌面版那样直接控制系统网络路由 |

**桌面版的节点控制更完整。** 网页版实现条件更复杂，只有页面提供有效备用来源时才能尝试恢复，改善空间和效果更难保证；网页版本不能代替桌面版。两者均无法保证任何网络环境完全不卡顿。

## 下载和安装

[前往 GitHub Releases](https://github.com/SkillGodAk/DRO/releases/latest)

- `DRO_Desktop_20260921.zip`：Windows 桌面版。完整解压，运行 `DRO_Desktop/DouyinRouteOptimizer.cmd`，根据提示授予管理员权限，保留 `Core/` 和 `Data/` 文件夹。
- `DRO_Web_0.7.6.zip`：Chrome 网页版 0.7.6。解压后先得到唯一的 `DRO` 文件夹，`manifest.json` 位于 `DRO/manifest.json`；进入 `chrome://extensions`，开启开发者模式，加载 **`DRO` 文件夹**；支持 Chrome 116+。加载后运行一次 `DRO/updater/Install-AutoUpdate.cmd`，之后 GitHub 发布较新的正式版时可自动下载、校验、覆盖并重新加载。0.7.5 用户这一次仍需手动更新到 0.7.6。

Chrome 扩展需要 JavaScript 才能运行，因此网页版 ZIP 内的脚本可以查看。

## 赞助作者

国外赞助：`r`n`r`n<a href="https://buymeacoffee.com/SkillGodAK"><img src="assets/donate-buymeacoffee.svg" alt="Buy Me a Coffee" width="180"></a>

银行收款：<br><img src="assets/donate-bank.jpg" width="180" alt="银行收款">

微信收款：<br><img src="assets/donate-wechat.jpg" width="180" alt="微信收款">

DRO 为独立第三方工具，并非抖音或字节跳动官方产品。
