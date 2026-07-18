# 毛智龍 — 學術個人主頁

[![授權條款](https://img.shields.io/github/license/zl2811/zl2811.github.io?style=flat-square&logo=creative-commons&color=1769aa)](LICENSE)

[[English](README.md)] | [[简体中文](README_zh_Hans.md)] | [[繁體中文](README_zh_Hant.md)]

本儲存庫包含[毛智龍學術個人主頁](https://zl2811.github.io/)的原始碼，使用 GitHub Pages 託管。

## 學術簡介

- **單位：** 國防科技大學大數據與決策實驗室
- **身分：** 人工智慧專業碩士研究生
- **研究方向：** 小樣本學習、類別增量學習、因果表徵學習與圖像識別

## 代表性論文

- **CVPR 2026 Poster：** [Prototype-based Causal Intervention for Multi-Label Image Classification](https://openaccess.thecvf.com/content/CVPR2026/html/Li_Prototype-based_Causal_Intervention_for_Multi-Label_Image_Classification_CVPR_2026_paper.html) — [程式碼](https://github.com/JustinLiam/ProCI)
- **CVPR 2026 Findings：** [Dynamic Pseudo-Label Assignment and Consistent Prototypical Learning for Few-Shot Class-Incremental Learning](https://openaccess.thecvf.com/content/CVPR2026F/html/Mao_Dynamic_Pseudo-Label_Assignment_and_Consistent_Prototypical_Learning_for_Few-Shot_Class-Incremental_CVPRF_2026_paper.html) — [程式碼](https://github.com/zl2811/DPCL)
- **AAAI 2026 Oral：** [A Causal Target for Learning to Defer under Hidden Confounding](https://ojs.aaai.org/index.php/AAAI/article/view/39493) — [程式碼](https://github.com/JustinLiam/CTLD)

## 主頁功能

- 適配桌面與行動裝置的響應式學術主頁版面
- 依照系統設定自動切換淺色與深色模式
- 完整展示論文框架圖，並提供論文、程式碼及專案頁面連結
- 支援鍵盤導覽、語意化標籤與減少動畫偏好
- 完善搜尋引擎及社群分享中繼資料

## 儲存庫結構

- `_config.yml` — 個人資訊、連結、中繼資料與主題設定
- `index.md` — 個人簡介、研究方向與新聞動態
- `_data/publications.yml` — 論文資訊與資源連結
- `_includes/` — 論文與獲獎情況元件
- `_layouts/homepage.html` — 頁面結構與個人資訊側欄
- `_sass/` 和 `assets/css/` — 響應式淺色/深色樣式
- `assets/img/` — 頭像、圖示與論文框架圖

## 維護說明

1. 在 `_config.yml` 中更新個人資訊和社群連結。
2. 在 `index.md` 中更新個人簡介、研究方向與新聞。
3. 將論文框架圖放入 `assets/img/`，再更新 `_data/publications.yml`。
4. 在 `_includes/selected_awards.md` 中更新獲獎情況。
5. 如有需要，替換 `assets/img/` 中的頭像與網站圖示。

安裝 Ruby 與 Bundler 後，可透過以下命令在本機預覽：

```bash
bundle install
bundle exec jekyll serve
```

GitHub Pages 會從 `main` 分支自動部署主頁。

## 致謝

本主頁基於 [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll 主題建置。
