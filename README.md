# NextGen Wellness Circle 2027｜品牌合作提案（Scroll Sales Kit）

GirlStyle 女生日常 × GSVIP 2027 招商網頁。單頁、純靜態（HTML + 圖片），唔使任何 build 工具，直接放上 GitHub Pages 就用得。

## 檔案結構

```
index.html      ← 成個網頁（CSS／JS 都喺入面）
assets/         ← 相片、logo、手寫字 PNG、活動影片（post1.mp4）
og-cover.jpg    ← WhatsApp／社交平台分享預覽圖（1200×630）
.nojekyll       ← 叫 GitHub Pages 唔好用 Jekyll 處理
```

外部載入：Google Fonts（Anton、Noto Sans TC、DM Sans）同 GSAP 3.12.5（cdnjs）。

## 放上 GitHub Pages（約 5 分鐘）

1. 喺 GitHub 開一個新 repository，例如 `nextgen-wellness-2027`，揀 **Public**。
2. 撳 **Add file → Upload files**，將呢個資料夾入面**所有嘢**拖入去（包括 `assets` 資料夾同 `.nojekyll`），然後 **Commit changes**。
   - Mac 預設會隱藏 `.nojekyll`，睇唔到都唔緊要，冇咗都照用得。
3. 去 **Settings → Pages** → Source 揀 **Deploy from a branch** → Branch 揀 `main`、資料夾 `/ (root)` → **Save**。
4. 等 1–2 分鐘，網址會係：`https://<你的 GitHub 帳號>.github.io/nextgen-wellness-2027/`

> 用公司 GitHub organization 開都得，網址會變成 `https://<org名>.github.io/nextgen-wellness-2027/`。想用自己域名（例如 `2027.girlstyle.com`）可以喺 Settings → Pages → Custom domain 設定。

## 出街前要填嘅位（仍然係方括號）

喺 `index.html` 用「搜尋 / 取代」處理：

| 位置 | 換成 |
|---|---|
| `[SITE_URL]` | 上線後嘅網址（要以 `/` 結尾），WhatsApp 預覽圖先會出到 |
| `[WHATSAPP_NUMBER]` | WhatsApp 號碼，國際格式唔使 `+`，例如 `852XXXXXXXX` |
| `[BOOKING_LINK]` | 預約會議連結（Calendly／Google Calendar 預約頁） |
| `[EMAIL]` | 聯絡電郵 |
| `[聯絡人名字 · 職位]` | 聯絡人 |

另外仍待確認：Q1 各場「場地洽談中」、Q1 主題及描述（草稿）、所有數字（4,500+、286%、96%、800K+／500+／100+）以最新紀錄為準；合作品牌名稱及相片使用已獲品牌同意。

## 之後點改

- **改字**：喺 GitHub 打開 `index.html` → 撳鉛筆 ✏️ → 搜尋要改嘅字 → Commit。1–2 分鐘後網頁自動更新。
- **換相**：上載新相到 `assets/`，用**同一個檔名**覆蓋，就唔使改 HTML。建議闊度 ≤ 2000px、JPG。
- 改完記得用手機同電腦各睇一次（Mobile 有獨立排版）。

## 分享建議

- WhatsApp／EDM 直接貼網址；填好 `[SITE_URL]` 後會顯示 `og-cover.jpg` 預覽。
- 第一次載入約 7MB（主要係相片同影片），建議用 Wi-Fi 測試一次。
