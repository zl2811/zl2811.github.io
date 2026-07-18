# 毛智龙 — 学术个人主页

[![许可证](https://img.shields.io/github/license/zl2811/zl2811.github.io?style=flat-square&logo=creative-commons&color=1769aa)](LICENSE)

[[English](README.md)] | [[简体中文](README_zh_Hans.md)] | [[繁體中文](README_zh_Hant.md)]

本仓库包含[我的学术个人主页](https://zl2811.github.io/)源代码。我是国防科技大学大数据与决策实验室人工智能专业硕士研究生，主要研究方向为**小样本类别增量学习（FSCIL）**、持续学习和计算机视觉。

## 快速使用

1. [Fork 本仓库](https://github.com/zl2811/zl2811.github.io/fork)。
2. 将仓库重命名为 `<你的用户名>.github.io`。
3. 修改 `_config.yml`，替换姓名、单位、邮箱、头像、CV 和社交链接。
4. 修改 `index.md` 中的个人简介、研究方向和新闻；在 `_data/publications.yml` 中维护论文信息。
5. 将头像和论文图片放入 `assets/img/`，然后提交并推送到 `main` 分支。

如果主页没有自动发布，请进入 **Settings → Pages**，选择 **Deploy from a branch**，并设置为 `main` 分支和 `/ (root)` 目录。随后即可通过 `https://<你的用户名>.github.io/` 访问主页。

## 本地预览（可选）

安装 Ruby 和 Bundler 后运行：

```bash
bundle install
bundle exec jekyll serve
```

随后在浏览器中打开 `http://localhost:4000`。

## 关键文件

- `_config.yml` — 个人资料、链接、元数据和外观设置
- `index.md` — 个人简介、研究方向和新闻
- `_data/publications.yml` — 论文信息与资源
- `_includes/selected_awards.md` — 获奖情况
- `assets/img/` — 头像、二维码、网站图标和论文框架图
- `_layouts/` 与 `_sass/` — 页面布局和样式

## 致谢

本主页基于 [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll 主题构建，并由 GitHub Pages 托管。
