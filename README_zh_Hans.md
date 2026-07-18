# 毛智龙 — 学术个人主页

[![许可证](https://img.shields.io/github/license/zl2811/zl2811.github.io?style=flat-square&logo=creative-commons&color=1769aa)](LICENSE)

[[English](README.md)] | [[简体中文](README_zh_Hans.md)] | [[繁體中文](README_zh_Hant.md)]

本仓库包含[毛智龙学术个人主页](https://zl2811.github.io/)的源代码，使用 GitHub Pages 托管。

## 学术简介

- **单位：** 国防科技大学大数据与决策实验室
- **身份：** 人工智能专业硕士研究生
- **研究方向：** 小样本学习、类别增量学习、因果表征学习与图像识别

## 代表性论文

- **CVPR 2026 Poster：** [Prototype-based Causal Intervention for Multi-Label Image Classification](https://openaccess.thecvf.com/content/CVPR2026/html/Li_Prototype-based_Causal_Intervention_for_Multi-Label_Image_Classification_CVPR_2026_paper.html) — [代码](https://github.com/JustinLiam/ProCI)
- **CVPR 2026 Findings：** [Dynamic Pseudo-Label Assignment and Consistent Prototypical Learning for Few-Shot Class-Incremental Learning](https://openaccess.thecvf.com/content/CVPR2026F/html/Mao_Dynamic_Pseudo-Label_Assignment_and_Consistent_Prototypical_Learning_for_Few-Shot_Class-Incremental_CVPRF_2026_paper.html) — [代码](https://github.com/zl2811/DPCL)
- **AAAI 2026 Oral：** [A Causal Target for Learning to Defer under Hidden Confounding](https://ojs.aaai.org/index.php/AAAI/article/view/39493) — [代码](https://github.com/JustinLiam/CTLD)

## 主页功能

- 适配桌面端与移动端的响应式学术主页布局
- 根据系统设置自动切换浅色与深色模式
- 完整展示论文框架图，并提供论文、代码和项目页面链接
- 支持键盘导航、语义化标签与减少动画偏好
- 完善搜索引擎和社交分享元数据

## 仓库结构

- `_config.yml` — 个人信息、链接、元数据和主题设置
- `index.md` — 个人简介、研究方向和新闻动态
- `_data/publications.yml` — 论文信息与资源链接
- `_includes/` — 论文和获奖情况组件
- `_layouts/homepage.html` — 页面结构与个人信息侧栏
- `_sass/` 和 `assets/css/` — 响应式浅色/深色样式
- `assets/img/` — 头像、图标和论文框架图

## 维护说明

1. 在 `_config.yml` 中更新个人信息和社交链接。
2. 在 `index.md` 中更新个人简介、研究方向和新闻。
3. 将论文框架图放入 `assets/img/`，随后更新 `_data/publications.yml`。
4. 在 `_includes/selected_awards.md` 中更新获奖情况。
5. 如有需要，替换 `assets/img/` 中的头像和网站图标。

安装 Ruby 和 Bundler 后，可通过以下命令在本地预览：

```bash
bundle install
bundle exec jekyll serve
```

GitHub Pages 会从 `main` 分支自动部署主页。

## 致谢

本主页基于 [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll 主题构建。
