# 毛智龍 — 學術個人主頁

[![授權條款](https://img.shields.io/github/license/zl2811/zl2811.github.io?style=flat-square&logo=creative-commons&color=1769aa)](LICENSE)

[[English](README.md)] | [[简体中文](README_zh_Hans.md)] | [[繁體中文](README_zh_Hant.md)]

本儲存庫包含[我的學術個人主頁](https://zl2811.github.io/)原始碼。我是國防科技大學大數據與決策實驗室人工智慧專業碩士研究生，主要研究方向為**小樣本類別增量學習（FSCIL）**、持續學習與電腦視覺。

## 快速使用

1. [Fork 本儲存庫](https://github.com/zl2811/zl2811.github.io/fork)。
2. 將儲存庫重新命名為 `<你的使用者名稱>.github.io`。
3. 修改 `_config.yml`，替換姓名、單位、電子郵件、頭像、CV 與社群連結。
4. 修改 `index.md` 中的個人簡介、研究方向與新聞；在 `_data/publications.yml` 中維護論文資訊。
5. 將頭像與論文圖片放入 `assets/img/`，然後提交並推送至 `main` 分支。

如果主頁沒有自動發布，請進入 **Settings → Pages**，選擇 **Deploy from a branch**，並設定為 `main` 分支與 `/ (root)` 目錄。隨後即可透過 `https://<你的使用者名稱>.github.io/` 存取主頁。

## 本機預覽（可選）

安裝 Ruby 與 Bundler 後執行：

```bash
bundle install
bundle exec jekyll serve
```

隨後在瀏覽器中開啟 `http://localhost:4000`。

## 關鍵檔案

- `_config.yml` — 個人資料、連結、中繼資料與外觀設定
- `index.md` — 個人簡介、研究方向與新聞
- `_data/publications.yml` — 論文資訊與資源
- `_includes/selected_awards.md` — 獲獎情況
- `assets/img/` — 頭像、QR Code、網站圖示與論文框架圖
- `_layouts/` 與 `_sass/` — 頁面版面與樣式

## 致謝

本主頁基於 [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll 主題建置，並由 GitHub Pages 託管。
