# sbsspark-backup 說明網站

供 Google OAuth Branding 使用的靜態網站，包含工具首頁及隱私權政策。內容依 `~/Documents/BACKUP.md` 的既定備份方式撰寫。

## 檔案

- `index.html`：應用程式用途、Google Drive 權限及聯絡方式。
- `privacy.html`：資料處理、保留與撤銷授權方式。
- `style.css`：兩頁共用的樣式。
- `.nojekyll`：讓 GitHub Pages 直接提供靜態檔案。

## 發布

使用公開 repo `willy970313/sbsspark-backup`，由 `main` 分支的根目錄發布 GitHub Pages。

- 首頁：<https://willy970313.github.io/sbsspark-backup/>
- 隱私權政策：<https://willy970313.github.io/sbsspark-backup/privacy.html>

Google Cloud 的 Branding 填入上述兩個網址；Authorized domains 填 `willy970313.github.io`，不含協定與路徑。回到 Audience 後發布為 In production。若 Console 另外要求網域所有權驗證，依當時提示處理。

修改網站後，以同一個 repo 提交及推送，並確認兩頁與樣式均回應 HTTP 200。OAuth 設定與授權仍由使用者完成；Drive 首次正式上傳仍須先呈報 dry run，取得使用者 OK。

## 資料界線

此 repo 只收錄網站檔案。備份內容、機器上的設定檔及 OAuth 憑證都保留在原定位置。
