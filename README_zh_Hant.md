# 個人學術主頁

\[[English](README.md)\] | \[[简体中文](README_zh_Hans.md)\] | \[[繁體中文](README_zh_Hant.md)\]

本倉庫包含我的個人學術主頁源代碼，透過 GitHub Pages 進行自動部署與託管。

## 個人簡介
- **機構：** 國防科技大學 大數據與決策實驗室
- **職位：** 人工智能碩士研究生
- **研究方向：** - 小樣本類增量學習 (Few-shot Class-incremental Learning)
  - 機器學習 (Machine Learning)

## 主要修改說明
- **研究方向：** 在「關於我」和「新聞」之間新增了專門的 Research Interests 板塊。
- **獲獎情況：** 將原有的「服務 (Service)」板塊替換為「獲獎情況 (Selected Awards)」。
- **社交連結：** 僅展示 GitHub；Google Scholar、CV、X 和 LinkedIn 資訊已在配置中保留（已註解隱藏），便於後續隨時啟用。

## 維護手冊

### 1. 修改基本資訊與社交連結
編輯 `_config.yml` 檔案。如需在未來啟用其他連結，只需刪掉對應程式碼行首的 `#` 註解符號即可。

### 2. 修改首頁文字內容
編輯 `index.md` 來更新「關於我 (About Me)」、「研究方向 (Research Interests)」以及「新聞動態 (News)」。

### 3. 更新論文
1. 將論文的預覽截圖放入 `assets/img/` 資料夾。
2. 在 `_data/publications.yml` 中添加或修改論文的具體資訊。

### 4. 更新獲獎資訊
編輯 `_includes/selected_awards.md` 檔案，列出你的最新榮譽與獎項。

### 5. 更換頭像與圖標
替換 `assets/img/` 目錄下的 `avatar.png`（個人頭像）和 `favicon.png`（瀏覽器標籤頁小圖標）。

## 致謝
本網站基於 [Minimal Light](https://github.com/yaoyao-liu/minimal-light) 主題修改構建。