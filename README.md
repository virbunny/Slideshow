# 米兔音樂相簿 PWA V58

## 使用方式

1. 將整個資料夾內的檔案上傳到同一個網站目錄。
2. 從瀏覽器開啟 `index.html`。
3. 手機瀏覽器選擇「加入主畫面」或「安裝應用程式」。

## 注意

- PWA 需要透過 HTTPS 或 localhost 執行；直接用本機檔案開啟時，Service Worker 通常不會啟用。
- 本版使用全新 icon 檔名：`mitu-music-album-icon-v58-192.png`、`mitu-music-album-icon-v58-512.png`。
- manifest 只放新的透明 PNG icon，沒有 maskable 圖示。
- service worker 快取名已更新為 `mitu-music-album-pwa-v58`。
- 若手機已安裝舊版 PWA，請刪除舊 PWA／舊捷徑，並清除網站資料或快取後再重裝。
