# 🛡️ ID Watermark Tool｜證件浮水印工具

> 本機端處理的證件浮水印工具，圖片完全不上傳、不經過任何伺服器。

**作者：Weber**

🔗 **線上使用：** [https://weber-yuan.github.io/id-watermark-tool/id-watermark-tool.html](https://weber-yuan.github.io/id-watermark-tool/id-watermark-tool.html)

---

## ✨ 功能特色

- 🔒 **100% 本機處理** — 所有圖片運算在瀏覽器內完成，不傳送至任何伺服器
- 🪪 **正反面分別處理** — 支援身分證、駕照正面與反面各自上傳、各自下載
- ✏️ **自訂浮水印文字** — 多行文字，自動附加當天日期
- 🎨 **彈性樣式設定** — 顏色、透明度、字體大小均可調整
- 📐 **三種浮水印模式** — 斜線鋪滿 / 單行指定位置 / 兩者同時
- 📁 **PNG / JPG 輸出** — 可選擇輸出格式，JPG 可調整品質以控制檔案大小
- 📱 **跨平台** — 電腦、手機（Android / iOS）均可用瀏覽器直接開啟使用

---

## 🚀 使用方式

### 方式一：線上版（GitHub Pages）

直接開啟網址，無需下載：

👉 [https://weber-yuan.github.io/id-watermark-tool/id-watermark-tool.html](https://weber-yuan.github.io/id-watermark-tool/id-watermark-tool.html)

### 方式二：下載本機使用（最安全）

1. 下載 [`id-watermark-tool.html`](./id-watermark-tool.html)
2. 用瀏覽器（Chrome / Safari / Edge）開啟，**不需要安裝任何軟體**
3. 可完全離線使用

---

## 📖 操作說明

1. **設定浮水印文字**：在「浮水印設定」區塊輸入文字，可多行（Enter 分行）
2. **選擇模式**：斜線鋪滿（防裁切）、單行指定位置，或兩者同時
3. **調整樣式**：顏色、透明度、字體大小
4. **上傳證件**：切換「正面」／「反面」分頁，上傳對應圖片
5. **處理並下載**：點擊「加入浮水印」後預覽，確認無誤後點「下載」

---

## 🔐 安全說明

本工具設計核心原則為**資料不離開使用者裝置**：

- 純前端 HTML + JavaScript，無後端伺服器
- 無任何網路請求（圖片處理完全不需要網路）
- 無 Cookie、無追蹤、無第三方服務
- 下載 `.html` 檔後斷網亦可正常運作

---

## 💡 浮水印建議格式

申辦不同業務時，建議浮水印文字包含**用途 + 機構名稱 + 日期**，例如：

```
申請中華電信門號專用
2025/04/30
```

```
開立銀行帳戶專用
台灣銀行
2025/04/30
```

> 實際格式請以各機構要求為準。

---

## 📄 License

MIT License — 自由使用、修改、散布。
