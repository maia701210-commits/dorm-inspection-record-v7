# 宿舍巡檢紀錄 V7

這是 V6_03 的獨立 V7 版本，不會覆蓋原本 V6 網址。

## V7 新功能
- 「✏️ 修改房號／位置」不限次數。
- 修改後不用重新拍照。
- 會重新產生壓字照片與正確檔名。
- 即使「結束本次巡檢」後，只要巡檢紀錄尚未刪除，仍可修改既有房間。
- 已結束的巡檢不能再新增照片。
- 避免同一次巡檢出現兩個相同房號／位置。
- APP／網頁名稱統一為「宿舍巡檢紀錄」。
- 使用獨立 IndexedDB 資料庫 `DormInspectionDB_V7`，不會直接與 V6 資料混在一起。
- 不使用 Google Drive、登入或雲端上傳。

## 部署
將本資料夾所有檔案上傳到新的 GitHub repository，並用 GitHub Pages 發布。
建議 repository 名稱：`dorm-inspection-record-v7`

## 注意
- 必須透過 HTTPS 網址使用，PWA 安裝與 Service Worker 才能正常工作。
- 相機功能在手機上建議使用最新版 Google Chrome。
- 不要把 V7 檔案覆蓋到 V6 repository。
