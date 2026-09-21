<p align="center"><img src="assets/dro-icon-seamless.png" alt="DRO" width="120"></p>

# DRO — 抖音播放優化工具

**繁體中文** | [简体中文](README.zh-CN.md) | [English](README_EN.md)

DRO 提供兩種獨立工具：**Windows 抖音桌面版**與**Chrome 抖音網頁版**。兩者的運作方式不同，請依照使用的抖音版本選擇對應下載；這個公開專案提供介紹及安裝成品，不公開完整開發工作區與獨立桌面版原始碼。

## 桌面版與網頁版有什麼不同？

| 項目 | Windows 桌面版 | Chrome 網頁版 |
| --- | --- | --- |
| 適用對象 | Windows 抖音桌面程式 | Chrome 的 www.douyin.com／live.douyin.com |
| 介入方式 | 在 Windows 端監測連線與節點品質，依判斷暫時封鎖不良節點、促使重新選路 | 在網頁播放器的可用範圍內觀察播放狀態，卡住時嘗試頁面已提供的同片備援來源 |
| 控制範圍 | 可使用 Windows 網路過濾機制；需要系統管理員授權 | 受瀏覽器、網站播放器、媒體網址與頁面提供的來源限制，不會直接控制系統網路路由 |
| 使用方式 | 執行程式，可選靜默或顯示監測資訊 | 安裝擴充功能，可在頁面開關並查看播放／下一支狀態 |

**如何選擇？** 使用 Windows 抖音桌面程式，請下載桌面版：它能直接介入節點封鎖，控制能力較完整。網頁版要受到 Chrome 與抖音網頁播放器限制，備援切換條件較苛刻，**改善空間和穩定性不如桌面版容易掌握**；網頁版不能當成桌面版的等效替代品。兩者都不能保證所有影片或所有網路環境完全不卡頓，也不會憑空增加 CDN 頻寬。

## 下載成品

[**前往 GitHub Releases**](https://github.com/SkillGodAk/DRO/releases/latest)

| 下載檔案 | 版本與用途 |
| --- | --- |
| `DRO_Desktop_20260921.zip` | Windows 桌面版，2026/09/21 封裝 |
| `DRO_Web_0.7.5.zip` | Chrome 網頁版 0.7.5，適用 Chrome 116 以上 |

## 安裝方式

**桌面版：** 下載 `DRO_Desktop_20260921.zip`，完整解壓縮，執行 `DRO_Desktop/DouyinRouteOptimizer.cmd`。請保留 `Core/` 及 `Data/` 資料夾，首次使用可能要求系統管理員權限。桌面版可依設定開啟靜默監測、調整冷卻時間或查看節點品質紀錄。

**網頁版：** 下載 `DRO_Web_0.7.5.zip` 並解壓到固定位置；解壓後會先看到唯一的 `DRO` 資料夾，`manifest.json` 位於 `DRO/manifest.json`。進入 Chrome `chrome://extensions`，啟用「開發人員模式」，按「載入未封裝項目」，**選取 `DRO` 資料夾**。網頁版提供播放／下一支就緒顯示、有限次卡頓恢復及直播狀態顯示；只有播放器提供可用的同片備援來源時才可能切換。

> Chrome 擴充功能執行時必須包含 JavaScript，因此網頁版 ZIP 中的腳本可被查看；本專案不另外上傳私人開發工作區與桌面版原始碼。

## 贊助作者

如果 DRO 對你有幫助，歡迎自願支持獨立開發者。

**國外贊助：** [Buy Me a Coffee](https://buymeacoffee.com/SkillGodAK)

**銀行收款：**

<img src="assets/donate-bank.jpg" alt="銀行贊助 QR Code" width="300">

**微信收款：**

<img src="assets/donate-wechat.jpg" alt="微信贊助 QR Code" width="300">

---

DRO 是獨立第三方工具，與抖音／字節跳動沒有官方隸屬或背書關係。
