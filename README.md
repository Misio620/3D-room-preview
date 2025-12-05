# 3D-room-preview
3D 房間佈局預覽 (3D Room Preview)

這是一個基於 WebGL (Three.js) 的 3D 房間互動專案。該專案將手繪的房間平面圖轉化為立體的 3D 空間，讓使用者可以直接在瀏覽器中預覽、旋轉視角，甚至移動家具來規劃佈局。

✨ 特色功能

全 3D 互動視角：使用滑鼠左鍵拖曳旋轉場景，右鍵平移，滾輪縮放。

可拖曳家具：實作了 DragControls，使用者可以點擊並拖曳房間內的家具（如床、桌椅、盆栽）來重新擺放位置。

智能移動限制：拖曳物品時會自動鎖定 Y 軸高度，確保家具貼合地板移動，不會飄在空中。

即時光影渲染：包含環境光與平行光，呈現自然的陰影效果。

無需安裝：純靜態 HTML/JS 網頁，開啟瀏覽器即可執行。

🛠️ 使用技術

HTML5 / CSS3

Three.js (v128) - 3D 引擎

OrbitControls - 軌道控制器 (視角)

DragControls - 拖曳控制器 (互動)

🚀 如何執行

預覽 (線上)

(您可以將您的 GitHub Pages 網址貼在這裡，例如：)
點擊這裡查看線上 Demo

本地端執行

下載此倉庫的程式碼。

找到 index.html (原 room_preview.html) 檔案。

直接使用瀏覽器 (Chrome, Edge, Firefox 等) 開啟該檔案即可。

注意：雖然直接開啟檔案通常可以運行，但在某些瀏覽器安全性限制下，載入本地資源可能會受限。建議使用 VS Code 的 "Live Server" 插件來執行會更穩定。

📦 部署到 GitHub Pages

本專案完全支援 GitHub Pages 免費託管：

將主檔案命名為 index.html。

將程式碼上傳至 GitHub 公開倉庫。

在倉庫設定 (Settings) > Pages 中，將 Source 設定為 main 分支。

等待部署完成即可獲得專屬網址。

📝 授權

本專案採用 MIT License 授權，歡迎自由修改與使用。
