<p align='center'>
  <img src='https://raw.githubusercontent.com/chen-yingfa/hexo-theme-fengye/main/source/images/logo.svg' alt='Hexo-theme-fengye' width='80'/>
</p>

<p align='center'>
Minimalistic but powerful Hexo theme
</p>

<p align='center'>
<a href="https://chen-yingfa.github.io">Demo</a>
</p>

<p align='center'>
  <b>English</b> | <a href="https://github.com/chen-yingfa/hexo-theme-fengye/blob/main/README.zh-CN.md">中文</a>
</p>

## Features

- 📦 Out of the box - Almost zero configuration.
- 🎨 Automatically switched light and dark theme.
- 💻 Auto fit Mobile and Screen responsively.
- 💹 Baidu/Google Analytics
- ⚗️ [MathJax Support](http://docs.mathjax.org/en/latest/)
- ⚡️ [Mermaid Support](https://mermaid-js.github.io/mermaid)
- 🖼️ [Fancybox Support](https://fancyapps.com/docs/ui/fancybox)
- 🦜 [Giscus Support](https://giscus.app/zh-CN)
- 📊 [ECharts Support](https://echarts.apache.org/)

## Installation

- Step 1: pull the repo from GitHub

```bash
cd your-blog/themes
git clone git@github.com:chen-yingfa/hexo-theme-fengye.git themes/fengye
```

- Step 2: Modify `theme` setting in `_config.yml` to `fengye`.

```diff
_config.yml
- theme: some-theme
+ theme: fengye
```

## Configuration

```yaml
# Header
nav:
  # Home: /index
  Posts: /archives
  Publications: /publications  # This renders `source/publications.md`
  "About Me": /about  # This renders `source/about.md`
  Categories:
    path: /category
    icon: mingcute:classify-2-fill
  Tags:
    path: /tag
    icon: mingcute:tag-fill

email: "chenyingfa1999@qq.com"

# favicon
favicon: /favicon.ico

# logo
logo: /images/logo.svg

# links
links:
  Github: https://github.com/chen-yingfa
  ZhiHu: https://www.zhihu.com/people/chen-ying-fa-34
  # Twitter:
  # Weibo:

# analytics
google_analytics:
baidu_analytics:

# mathjax
fancybox: true

# mathjax
mathjax: true

# mermaid
mermaid:
  enable: true
  # Available themes: default | dark | forest | neutral
  theme: default

# giscus
giscus:
  enable: true
  repo:
  repo_id:
  category:
  category_id:
  mapping:
```

## Add Category and Tag Page

See the file `your-blog/themes/fengye/layout/category.ejs` and `your-blog/themes/fengye/layout/tag.ejs`.

## Acknowledgments

This is mostly based on the [Maple theme](https://www.github.com/xbmlz/hexo-theme-maple) by [xbmlz](https://www.github.com/xbmlz). There is much leftover code from this repo.
