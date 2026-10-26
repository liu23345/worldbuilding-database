# 造境誌｜角色與世界觀設定資料庫

## 功能
- 分類管理角色人物、勢力組織、地理地點、歷史傳說、物品概念
- 新增、查看詳細設定、編輯與刪除資料
- 搜尋名稱、簡介、詳細設定與標籤
- 依分類與標籤篩選
- 記錄世界觀備忘
- 匯出 JSON 備份
- 使用瀏覽器 localStorage 保存資料
- 響應式版面，支援手機與桌面

## 使用
直接在瀏覽器開啟 `index.html` 即可使用。

## Netlify 部署
1. 解壓縮專案 ZIP。
2. 開啟 https://app.netlify.com/drop 並登入 Netlify。
3. 將包含 `index.html` 的 `worldbuilding_database` 資料夾拖曳至部署區域。
4. 部署完成後，Netlify 會產生公開網址（格式通常為 `https://網站名稱.netlify.app`）。
5. 開啟網址測試新增、搜尋、分類篩選、編輯及 JSON 匯出。

## 注意
資料儲存在目前瀏覽器的 localStorage，不會自動同步到其他裝置。建議定期使用「匯出資料 JSON」備份。
