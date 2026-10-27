# 地瓜瓜の歌單 🍠 — GitHub Pages

此版以原先 fang-fang 網站的區塊配置為參考，維持搜尋、F 欄分類標籤、歌曲卡片、計數置中、複製及隨機抽歌功能，改為粉紅色日系少女風主題。

## 上傳
把 ZIP 解壓後的 `index.html`、`style.css`、`script.js`、`copyright.html`、`sakura-pink.png`、`.nojekyll` 直接上傳到 GitHub repository 根目錄；Settings → Pages → Deploy from a branch → main / (root)。

## 試算表
連接： https://docs.google.com/spreadsheets/d/1Fb3Ut6Vwz7YejhOjFpvXM0bobXP6wpYxhnjdfAf2vz0/edit

- A：歌名；B：歌手；C：分類；D：歌曲連結。
- F：分類按鈕名稱。
- H：設定名稱；I：設定內容。可以在 Google 試算表直接編輯，網頁重整讀取。
- H 欄可使用「網站小標題」、「抽歌視窗標題」、「關閉按鈕文字」，I 欄填寫對應內容。標題固定為地瓜瓜の歌單。
- 若資料所在工作表非 gid=0，請修改 `script.js` 的 `SHEET_GID`。

試算表需要設為「知道連結的任何人都可以檢視」，網站才有權讀取。H/I 在試算表中可編輯，但此網站不提供訪客直接回寫試算表（需另建授權後端）。為避免副標題閃舊資料，網站在成功讀取表格前不會顯示副標題，亦不會先顯示過期歌曲；Google 端同步時間仍非網站可控制。

## 版權
© 2026 LionLionTomato. All Rights Reserved.
