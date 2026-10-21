# 粉嶺官立中學｜設計與應用科技科｜粗幼線條技巧

課堂互動網頁，用來講解立體圖的粗幼線條法則。頁面以 Three.js 與 OrbitControls 顯示立體，拖曳可轉動視角，紅色粗線會按目前視角即時更新。介面為繁體中文，並附上校徽與工作紙參考圖。全站都是靜態檔案，可離線使用，無需安裝或連線。

## 在本機開啟

1. 複製此儲存庫，或下載 ZIP 並解壓。
2. 用瀏覽器開啟根目錄的 `index.html`（雙擊檔案，或把檔案拖進瀏覽器視窗）。
3. 拖曳轉動立體，以滾輪或雙指縮放。工具列可重設視角，以及顯示或隱藏紅粗線、幼線、法則說明與參考圖。

請保持 `index.html`、`school-crest.png`、`reference.png` 與 `vendor/` 在同一層，否則圖片與程式庫會載入失敗。

## 線上頁面

GitHub Pages：<https://neilfoto.github.io/thick-thin-lines/>

若連結尚未開啟，請到儲存庫 **Settings → Pages**，來源選 **Deploy from a branch**，分支選 **main**、資料夾選 **/ (root)**，然後儲存。部署通常需要一兩分鐘。

`vendor/` 內的 Three.js 與 OrbitControls 為 MIT 授權。
