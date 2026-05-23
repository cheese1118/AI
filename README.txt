# Collection-V4 PWA

## 版本
Collection-V4｜照片壓縮版

## 本版重點
- 以 PhotoGrid V3 為基礎
- 照片改為加入時自動壓縮
- 目標約可存 30 張照片左右
- 照片仍維持一列四張、往下排列
- 保留文字卡片、圖片分享、長按管理、備份還原、清除全部功能

## 照片壓縮設定
- 最大邊長：約 720px
- 輸出格式：JPEG
- 品質：約 0.68
- 用途：降低 iPhone Safari / PWA localStorage 容量壓力

## GitHub Pages 上傳方式
1. 解壓縮 ZIP
2. 將全部檔案覆蓋上傳到 GitHub Repository
3. 確認以下檔案都有更新：
   - index.html
   - manifest.json
   - sw.js
   - icon-192.png
   - icon-512.png
   - README.txt
4. Repository → Settings → Pages
5. Branch 選 main / root
6. 開啟 GitHub Pages 網址

## iPhone 更新提醒
如果 iPhone 還顯示舊版，請：
1. 刪除主畫面上的舊 Collection
2. 設定 → Safari → 進階 → 網站資料
3. 刪除你的 GitHub Pages 網站資料
4. 用 Safari 重新開啟網址
5. 分享 → 加入主畫面

## 確認是否為新版
畫面上會顯示：

版本：Collection-V4｜照片壓縮版
