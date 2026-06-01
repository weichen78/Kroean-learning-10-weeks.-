# 한국어 10週速成 — PWA

**首爾出發前完整準備 · Seoul-Ready in 10 Weeks**

---

## 部署到 GitHub Pages（5步驟）

### 1. 建立新 repo
- 到 github.com → 右上角 **+** → **New repository**
- Repository name：`korean-study`（或任何名字）
- 設為 **Public**
- 不要勾選 Initialize README
- 點 **Create repository**

### 2. 上傳檔案
把以下所有檔案上傳到 repo：
```
index.html
manifest.json
sw.js
icons/
  icon-192.png
  icon-512.png
```

上傳方式：在 repo 頁面點 **uploading an existing file**，把整個資料夾拖進去。

### 3. 開啟 GitHub Pages
- repo 頁面 → **Settings** → 左側 **Pages**
- Source 選 **Deploy from a branch**
- Branch 選 **main**，folder 選 **/ (root)**
- 點 **Save**

### 4. 等待部署（約 1–2 分鐘）
網址會是：`https://你的帳號.github.io/korean-study/`

### 5. iPhone 加入主畫面
- 用 **Safari** 打開網址
- 點下方 **分享圖示 □↑**
- 選 **加入主畫面**
- 名稱會自動填入「한국어」
- 點 **新增**

完成！桌面會出現深綠色 App 圖示。

---

## 注意事項
- 必須用 Safari 才能加入主畫面（Chrome 不支援 iOS PWA）
- 發音功能需要網路連線（使用 Google TTS）
- 學習進度儲存在瀏覽器 localStorage，換裝置不會同步
