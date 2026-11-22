# AI 作品館（GitHub Pages → Android APK 套件）

此壓縮包已包含完整 PWA 與 PNG 圖示，可直接上載至 GitHub 並轉換為 Android `.apk`：

## 3 步轉成 Android `.apk`
1. **上載至 GitHub**：在 GitHub 建立一個 Public Repository，把壓縮包內所有檔案（`index.html`、`manifest.json`、`sw.js`、`icon-192.png`、`icon-512.png`）上載到根目錄。
2. **啟用 GitHub Pages**：進入 Repo 的 **Settings → Pages**，在 Branch 選擇 `main` → `/ (root)` 並按 Save，約 1 分鐘後取得 `https://<你的帳號>.github.io/<repo名稱>/` 網址。
3. **一鍵打包 `.apk`**：前往 https://www.pwabuilder.com/ ，貼上你的 GitHub Pages 網址 → 按 **Start** → 選 **Package for stores → Android** → 點 **Generate Package**，即可下載內含已簽署 `.apk` 的壓縮檔並安裝到 Android 手機。

## iOS / iPadOS / 電腦使用
直接用 Safari 或 Chrome 開啟同一個 GitHub Pages 網址，點「加入主畫面」即可全螢幕使用，並可透過設定內的 **GitHub Gist 雲端同步** 或 **`.json` 備份** 跨裝置同步。
