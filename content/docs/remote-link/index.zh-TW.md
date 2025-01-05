---
ShowToc: true
aliases:
- docs/remote-link/index.zh-tw.md
copy_mark: src
date: 2024-05-25
title: 如何使用“連線”功能?
---

“連線”功能可以將你的應用資料對映為 PC 上的一個資料夾，使得你可以用 PC 的軟體來編輯你的文字。

該功能基於通用的 WebDav 協議實現，你可以使用作業系統自帶的對映邏輯或者任何你熟悉的第三方工具來完成對映。以下簡單介紹部分較為簡便的對映方式。

## Windows

在 Windows 平臺這裡推薦使用 RaiDrive 這款第三方工具。你可以透過下方的地址來下載安裝包：

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

（1.8.0 並不是最新版，但它功能齊全更重要的是它沒有廣告）

安裝開啟後你可以看到如下介面，接著按照下面步驟操作：

![RaiDrive setup](/img/add_drive.zh-TW.webp)

1. 點選頂部“新增”按鈕進入對映配置流程
2. 選擇“NAS”並選中“WebDav”協議
3. 選擇對映資料夾的硬碟符和名稱
4. 輸入對映地址
    - 在“地址”字樣的右側你可以看到一個覈取方塊，該框是用於切換 http 和 https 協議的，**請確保它處於未選中的狀態**，此時協議未 **http**
    - 輸入到右側的位址列和埠號。截圖中的地址和埠僅供參考，請以啟動應用“連線”功能後介面顯示的為準。
    - “路徑”一欄可以留空
5. 輸入你自定義的使用者名稱和密碼，如果沒有的話可以勾選“匿名”覈取方塊
6. 點選“確定”按鈕以啟動對映

如果一切順利則在成功後會自動開啟對映目錄，如下圖所示：

![Done](/img/done.zh-TW.webp)

## Linux 或者 MacOS

待補充
