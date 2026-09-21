# DRO — Douyin Route Optimizer

[繁體中文](README.md) | [简体中文](README.zh-CN.md) | **English**

DRO offers two separate Douyin playback tools: a Chrome web extension (v0.7.5) and a Windows desktop utility (20260921 package). This public repository contains product documentation and downloadable builds, not the private development workspace or standalone source files.

## Downloads

[GitHub Releases](https://github.com/SkillGodAk/DRO/releases)

- `DRO_Web_Playback_0.7.5.zip`: Chrome 116+ for www.douyin.com and live.douyin.com.
- `DRO_Desktop_20260921.zip`: Windows desktop Douyin client.

The extension displays playback/next-video readiness and can try alternative sources already supplied for the same video when playback stalls. To install, unzip and open `chrome://extensions`, enable Developer mode, select **Load unpacked**, and choose the directory containing `manifest.json`. Executable JavaScript is inherently included in the extension ZIP and remains inspectable.

The Windows utility monitors local playback node quality and can temporarily avoid poor nodes. Unzip the desktop package and run `DRO_Desktop/DouyinRouteOptimizer.cmd`, accepting the administrator prompt if shown. Keep the `Core` and `Data` directories intact.

Neither tool guarantees completely uninterrupted playback on every network. Check [SHA256SUMS](SHA256SUMS) and [release notes](RELEASE_NOTES.md).

## Support the author

[Buy Me a Coffee](https://buymeacoffee.com/SkillGodAK)

Bank transfer QR:<br><img src="assets/donate-bank.jpg" width="300" alt="Bank donation">

WeChat QR:<br><img src="assets/donate-wechat.jpg" width="300" alt="WeChat donation">

Independent third-party tool; not officially affiliated with or endorsed by Douyin or ByteDance.