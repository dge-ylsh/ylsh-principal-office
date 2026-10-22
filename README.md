# 校長室故事頁（GitHub Pages 發布包）

此資料夾是校長室單欄故事頁的獨立發布包。頁面文字、內容順序與插圖沿用目前原型；發布入口為 `public/index.html`。GitHub Actions 會在推送到 `main` 後自動部署 `public` 目錄。

## 發布方式

1. 將本資料夾內的檔案放入一個 GitHub repository。
2. 將 repository 的預設分支設為 `main`，推送檔案。
3. 在 GitHub 的 Settings → Pages 確認由 GitHub Actions 發布。
4. 等待 Actions 的 Pages 部署完成，複製部署結果網址。

頁面本身不載入原始相片目錄、PDF 備份或首頁改版提案。網站若設為公開，頁面中校長簡歷、聯絡資訊與插圖將對外可見。
