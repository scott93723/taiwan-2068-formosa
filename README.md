# Taiwan 2068 Formoasa

一款以台灣地景為靈感、使用 Unreal Engine 製作的獨立互動作品。

## 太魯閣試玩版

走進以太魯閣峽谷為靈感打造的未來場景，探索峽谷公路、隧道、溪谷與觀景區域。

[下載 Windows 試玩版](https://github.com/scott93723/taiwan-2068-formosa/releases/tag/v0.1.1-rc2)

目前試玩包為 **v0.1.1-rc2**，包含太魯閣峽谷與景點選單。解壓後從 `Windows/Taipei2068.exe` 啟動；遊戲的原始執行檔名稱維持不變。

## 安裝

1. 從 Releases 下載 ZIP。
2. 將 ZIP 完整解壓縮。
3. 開啟 `Windows` 資料夾，執行 `Taipei2068.exe`。

需要 Windows 64 位元及支援 DirectX 12 / Shader Model 6 的顯示卡。

## 操作

| 按鍵 | 功能 |
| --- | --- |
| W / A / S / D | 行走 |
| 滑鼠 | 轉動視角 |
| 左 Shift / Space | 跑步 / 跳躍 |
| R | 回到景點起點 |
| Esc / 左鍵 | 釋放或重新鎖定滑鼠 |
| M | 開啟景點選單；第一頁按 8 返回太魯閣 |
| F5 | 儲存生命、電量與到訪紀錄 |
| 7 / Left Ctrl / 8 | 切換飛行 / 飛行下降 / 切換速度模式 |
| Alt + F4 | 離開遊戲 |

試玩包內其他景點顯示「尚未準備」。F5 不保存目前站立位置。

## 版本驗證

- Windows Shipping 原始啟動檔已完成本機 DirectX 12 畫面擷取：89 張 960 × 540 畫面，持續 12.8 秒。
- 封裝結構 17 / 17 項通過，啟動場景為太魯閣。
- 太魯閣路線與碰撞測試 47 / 47 項通過；這項是 2026-09-30 的 Unreal Editor Development 測試。

Shipping 啟動畫面驗證不等於完整操作測試或效能基準。詳見 [版本檔案與校驗資訊](release-manifest-v0.1.1-rc2.json) 及 [Shipping 測試證據](docs/qa/v0.1.1-rc2/shipping-boot-render.json)。

## 注意

本作品是獨立創作的開發中版本，不代表太魯閣國家公園管理處、任何政府機關或真實建築相關單位。場景為藝術化重現，不應作為道路、步道或旅遊安全資訊。
