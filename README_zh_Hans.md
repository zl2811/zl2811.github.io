# 个人学术主页

\[[English](README.md)\] | \[[简体中文](README_zh_Hans.md)\] | \[[繁體中文](README_zh_Hant.md)\]

本仓库包含我的个人学术主页源代码，通过 GitHub Pages 进行托管。

## 个人简介
- **机构：** 国防科技大学 大数据与决策实验室
- **职位：** 人工智能硕士研究生
- **研究方向：** - 小样本类增量学习 (Few-shot Class-incremental Learning)
  - 机器学习 (Machine Learning)

## 主要修改说明
- **研究方向：** 在“关于我”和“新闻”之间新增了专门的 Research Interests 板块。
- **获奖情况：** 将原有的“服务 (Service)”板块替换为“获奖情况 (Selected Awards)”。
- **社交链接：** 仅展示 GitHub；Google Scholar、CV、X 和 LinkedIn 信息已在配置中保留（已注释），便于后续启用。

## 维护手册

### 1. 修改基本信息与社交链接
编辑 `_config.yml`。如需在未来启用其他链接，只需删掉行首的 `#` 注释符号即可。

### 2. 修改首页文字
编辑 `index.md` 来更新“关于我”、“研究方向”以及“新闻”动态。

### 3. 更新论文
1. 将论文截图放入 `assets/img/`。
2. 在 `_data/publications.yml` 中添加论文信息。

### 4. 更新获奖信息
编辑 `_includes/selected_awards.md` 列出你的荣誉奖项。

### 5. 更换头像与图标
替换 `assets/img/` 目录下的 `avatar.png`（头像）和 `favicon.png`（浏览器图标）。

## 致谢
本站主题基于 [Minimal Light](https://github.com/yaoyao-liu/minimal-light) 修改。