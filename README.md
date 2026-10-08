# Mai Score

一個純靜態 maimai 國際版譜面與成績搜尋網站。打開 `index.html` 即可使用，也可以部署到任意靜態主機。

## 功能

- 搜尋歌曲、藝術家、分類或版本
- 按分類、版本、Standard/DX、難度、精確定數篩選
- 查看每首歌的 Standard 與 DX 譜面、精確定數、版本與音符數
- 在瀏覽器本地保存個人成績

## 資料來源

- 歌曲、封面與精確定數資料來自 [ArcadeSongs maimai](https://arcade-songs.zetaraku.dev/maimai/)
- 資料版本為國際版（International），更新時間 2026-10-04 18:46:46
- 收錄 1,491 首國際版可用歌曲與 6,128 張譜面
- 分類（genre）保留官方英文/日文名稱

## 本地執行

直接雙擊 `index.html`，或在該目錄執行任意靜態伺服器，例如：

```powershell
python -m http.server 8000
```

然後造訪 `http://localhost:8000`。

## GitHub Pages

1. 開啟 GitHub repository 的 **Settings** → **Pages**。
2. 將 **Source** 設為 `main` 分支與 `/ (root)`。
3. 儲存後使用 GitHub 提供的網址瀏覽網站。
