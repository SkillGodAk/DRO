<p align="center"><img src="assets/dro-icon.png" alt="DRO" width="120"></p>

# DRO — Douyin Route Optimizer

**繁體中文** | [简体中文](README.zh-CN.md) | [English](README_EN.md)

DRO 是獨立開發的抖音播放輔助工具，提供 **網頁版 Chrome 擴充功能**與 **Windows 桌面版**，兩者分開安裝與運作。本公開倉庫只提供產品資訊及已封裝成品，不公開開發工作區與獨立原始碼檔案。

## 版本與下載

[**前往 GitHub Releases 下載成品**](https://github.com/SkillGodAk/DRO/releases)

| 版本 | 適用環境 | 發佈檔案 |
| --- | --- | --- |
| 網頁版 0.7.5 | Chrome 116+；www.douyin.com 與 live.douyin.com | `DRO_Web_Playback_0.7.5.zip` |
| 桌面版（20260921 封裝） | Windows；抖音桌面程式 | `DRO_Desktop_20260921.zip` |

## 功能

**網頁版：** 顯示播放與下一支就緒狀態；遇到卡頓時嘗試播放器已提供的同片備援來源；包含直播狀態顯示。設計上避免全頁網路攔截和永久循環監測。

**桌面版：** 觀察節點品質、記錄本機學習結果，並可依設定暫時避開品質不佳的節點；包含靜默與可視監測模式。第一次啟動可能要求系統管理員權限。

兩版均無法保證任何網路條件下完全零卡頓；實際體驗取決於來源、所在地與網路狀態。

## 安裝

**網頁版：** 下載並解壓 `DRO_Web_Playback_0.7.5.zip` 至固定資料夾，開啟 Chrome 的 `chrome://extensions` → 啟用「開發人員模式」→「載入未封裝項目」，選取含 `manifest.json` 的解壓資料夾。擴充功能的 JavaScript 是 Chrome 執行所必需，隨 ZIP 提供且可查看；本倉庫不另外公開開發原始碼。

**桌面版：** 完整解壓 `DRO_Desktop_20260921.zip`，雙擊 `DRO_Desktop/DouyinRouteOptimizer.cmd`，依程式提示操作。請保留 `Core/` 與 `Data/` 資料夾，不要單獨取出 EXE。

發佈檔案 SHA256 請見 [SHA256SUMS](SHA256SUMS)，版本變更見 [RELEASE_NOTES.md](RELEASE_NOTES.md)。

## 贊助作者

如果 DRO 對你有幫助，歡迎自願支持獨立開發者。

**國外贊助：** [Buy Me a Coffee](https://buymeacoffee.com/SkillGodAK)

**銀行收款：**

<img src="assets/donate-bank.jpg" alt="銀行贊助 QR Code" width="300">

**微信收款：**

<img src="assets/donate-wechat.jpg" alt="微信贊助 QR Code" width="300">

---

DRO 是獨立第三方工具，與抖音／字節跳動沒有官方隸屬或背書關係。