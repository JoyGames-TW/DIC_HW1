# 周達弘 — 個人單頁網站

簡介
------

一個簡潔的單頁（Single Page）個人網站，展示作者名稱與學號，並在首頁顯示即時更新的本地時間；視覺風格為科幻 / 賽博龐克 / 未來感。

作者資訊
------

- 名稱：周達弘
- 學號：5112056037

線上示範（GitHub Pages）
------

- 已部署（GitHub Pages）： https://joygames-tw.github.io/DIC_HW1/

截圖
------

下方為部署後畫面快照：

![Site screenshot](assets/screen.png)

功能重點
------

- 顯示姓名與學號
- 即時時鐘（每秒更新，本地時間）
- 單一 HTML/CSS 檔案，無伺服端依賴

本機預覽
------

方法一（直接開啟）：在檔案總管中雙擊 `index.html` 即可於瀏覽器開啟。

方法二（使用簡易 HTTP 伺服器）：

```powershell
cd E:\Projects\DIC\DIC_HW1
python -m http.server 8000
# 然後開啟 http://localhost:8000
```

開發與部署
------

- 技術堆疊：HTML、CSS、少量 client-side JavaScript（時鐘）。
- 已設定 GitHub Pages（來源：`main` / 根目錄）。

提交與更新
------

若需更新網站內容，請在本地修改後 commit 並推送到 `main`：

```powershell
git add .
git commit -m "Update site"
git push origin main
```

聯絡
------

如需協助或樣式調整，請開 issue 或直接聯絡作者。
# 周達弘 - 個人單頁網站

說明：

- 作者：周達弘
- 學號：5112056037
- 功能：首頁顯示名稱、學號，並以即時時鐘顯示當前時間（每秒更新）。
- 技術：純 HTML、CSS（少量內嵌 JS 用於更新時鐘）。
- 風格：科幻 / 賽博龐克 / 未來感。

如何查看：

1. 在瀏覽器中開啟 `index.html`（雙擊或使用瀏覽器的開啟檔案功能）。
2. 若要在本機啟動簡易服務（選擇性），可使用 Python：

```powershell
cd E:\Projects\DIC\DIC_HW1
python -m http.server 8000
```

然後在瀏覽器開啟 http://localhost:8000。

Git 推送：

- 我已嘗試將此專案推送到 https://github.com/JoyGames-TW/DIC_HW1.git（若推送失敗，可能需要提供 GitHub 認證或 PAT）。


**Deployed site:** https://joygames-tw.github.io/DIC_HW1/

![Site screenshot](assets/site-screenshot.png)
