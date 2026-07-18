# Zhilong Mao — Academic Homepage

[![License](https://img.shields.io/github/license/zl2811/zl2811.github.io?style=flat-square&logo=creative-commons&color=1769aa)](LICENSE)

[[English](README.md)] | [[简体中文](README_zh_Hans.md)] | [[繁體中文](README_zh_Hant.md)]

This repository contains the source code for [Zhilong Mao's academic homepage](https://zl2811.github.io/), hosted with GitHub Pages.

## Academic Profile

- **Institution:** Laboratory for Big Data and Decision, National University of Defense Technology
- **Position:** Master's Student in Artificial Intelligence
- **Research Interests:** Few-shot learning, class-incremental learning, causal representation learning, and image recognition

## Featured Publications

- **CVPR 2026 Poster:** [Prototype-based Causal Intervention for Multi-Label Image Classification](https://openaccess.thecvf.com/content/CVPR2026/html/Li_Prototype-based_Causal_Intervention_for_Multi-Label_Image_Classification_CVPR_2026_paper.html) — [Code](https://github.com/JustinLiam/ProCI)
- **CVPR 2026 Findings:** [Dynamic Pseudo-Label Assignment and Consistent Prototypical Learning for Few-Shot Class-Incremental Learning](https://openaccess.thecvf.com/content/CVPR2026F/html/Mao_Dynamic_Pseudo-Label_Assignment_and_Consistent_Prototypical_Learning_for_Few-Shot_Class-Incremental_CVPRF_2026_paper.html) — [Code](https://github.com/zl2811/DPCL)
- **AAAI 2026 Oral:** [A Causal Target for Learning to Defer under Hidden Confounding](https://ojs.aaai.org/index.php/AAAI/article/view/39493) — [Code](https://github.com/JustinLiam/CTLD)

## Homepage Features

- Responsive academic layout for desktop and mobile devices
- Automatic light and dark color schemes
- Publication cards with full-resolution framework figures and paper/code links
- Accessible navigation, semantic markup, and reduced-motion support
- Updated metadata for search engines and social sharing

## Repository Structure

- `_config.yml` — profile, links, metadata, and theme settings
- `index.md` — biography, research interests, and news
- `_data/publications.yml` — publication metadata and resource links
- `_includes/` — publication and award sections
- `_layouts/homepage.html` — page structure and profile sidebar
- `_sass/` and `assets/css/` — responsive light/dark styling
- `assets/img/` — avatar, icons, and publication figures

## Maintenance

1. Update profile metadata and social links in `_config.yml`.
2. Edit biography, research interests, and news in `index.md`.
3. Add publication figures to `assets/img/`, then update `_data/publications.yml`.
4. Update awards in `_includes/selected_awards.md`.
5. Replace the avatar or favicons in `assets/img/` when needed.

To preview locally with Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

GitHub Pages deploys the homepage from the `main` branch.

## Acknowledgements

The homepage is based on the [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll theme.
