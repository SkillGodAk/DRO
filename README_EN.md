# DRO — Douyin Playback Optimizer

[繁體中文](README.md) | [简体中文](README.zh-CN.md) | **English**

DRO provides separate Windows desktop and Chrome web playback tools. This public repository contains release packages, usage information and author support links, not the private development workspace or standalone desktop source code.

## Desktop vs. web

| | Windows desktop | Chrome web |
| --- | --- | --- |
| Works with | Windows Douyin desktop application | www.douyin.com / live.douyin.com in Chrome |
| Technique | Checks connection/node quality and temporarily blocks poor nodes using Windows network filtering | Watches webpage player state and, after a stall, may retry an alternative source already offered for the same video |
| Limitations | Requires administrator permission for system-level network controls | Browser and website restrictions prevent equivalent system-wide routing control; alternatives are not always available |

**Desktop has more direct node-control capability.** The web edition faces stricter playback and browser constraints, so its potential improvement is less predictable and it is not an equivalent substitute for the desktop tool. Neither guarantees zero buffering across all videos, sources or networks.

## Downloads and installation

[GitHub Releases](https://github.com/SkillGodAk/DRO/releases/latest)

- `DRO_Desktop_20260921.zip` — Windows desktop package. Extract fully and launch `DRO_Desktop/DouyinRouteOptimizer.cmd`; keep `Core/` and `Data/` intact. Administrator permission may be required.
- `DRO_Web_0.7.5.zip` — Chrome web extension v0.7.5, Chrome 116+. Extract to a fixed directory, open `chrome://extensions`, enable Developer mode and **Load unpacked** from the folder containing `manifest.json`.

The web extension necessarily contains inspectable JavaScript in its runnable ZIP.

## Support the author

[Buy Me a Coffee](https://buymeacoffee.com/SkillGodAK)

Bank transfer QR:<br><img src="assets/donate-bank.jpg" width="300" alt="Bank donation">

WeChat QR:<br><img src="assets/donate-wechat.jpg" width="300" alt="WeChat donation">

DRO is an independent third-party tool and is not officially affiliated with or endorsed by Douyin or ByteDance.
