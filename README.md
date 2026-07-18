# Zhilong Mao — Academic Homepage

[![License](https://img.shields.io/github/license/zl2811/zl2811.github.io?style=flat-square&logo=creative-commons&color=1769aa)](LICENSE)

[[English](README.md)] | [[简体中文](README_zh_Hans.md)] | [[繁體中文](README_zh_Hant.md)]

This repository contains the source code for [my academic homepage](https://zl2811.github.io/). I am a Master's student in Artificial Intelligence at the Laboratory for Big Data and Decision, National University of Defense Technology. My research primarily focuses on **Few-Shot Class-Incremental Learning**, continual learning, and computer vision.

## Quick Start

1. [Fork this repository](https://github.com/zl2811/zl2811.github.io/fork).
2. Rename the fork to `<your-username>.github.io`.
3. Edit `_config.yml` to replace the name, affiliation, email, avatar, CV, and social links.
4. Edit `index.md` for the biography, research interests, and news; edit `_data/publications.yml` for publications.
5. Put avatars and paper figures in `assets/img/`, then commit and push to `main`.

If the site is not published automatically, open **Settings → Pages**, select **Deploy from a branch**, and choose `main` with the `/ (root)` folder. The homepage will then be available at `https://<your-username>.github.io/`.

## Local Preview (Optional)

With Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000` in a browser.

## Key Files

- `_config.yml` — profile, links, metadata, and appearance
- `index.md` — biography, research interests, and news
- `_data/publications.yml` — publication metadata and resources
- `_includes/selected_awards.md` — awards
- `assets/img/` — avatar, QR code, favicons, and paper figures
- `_layouts/` and `_sass/` — layout and styling

## Credits

Built with the [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll theme and hosted by GitHub Pages.
