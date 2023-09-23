<p align='center'>
  <img src='https://raw.githubusercontent.com/chen-yingfa/hexo-theme-fengye/main/source/images/logo.svg' alt='Hexo-theme-fengye' width='80'/>
</p>
<p align='center'>
  一款简约的 Hexo 主题
</p>
<p align='center'>
  <a href="https://chen-yingfa.github.io">演示站点</a>
</p>

<p align='center'>
<a href="https://github.com/chen-yingfa/hexo-theme-fengye/blob/main/README.md">English</a> | <b>中文</b>

</p>

## 特性

- 📦 开箱即用，几乎零配置
- 🎨 自动切换明/暗主题
- 💻 移动端自适应
- 💹 百度/谷歌分析统计
- ⚗️ [MathJax 支持](http://docs.mathjax.org/en/latest/)
- ⚡️ [Mermaid 支持](https://mermaid-js.github.io/mermaid)
- 🖼️ [Fancybox 支持](https://fancyapps.com/docs/ui/fancybox)
- 🦜 [Giscus Support](https://giscus.app/zh-CN)
- 📊 [ECharts 支持](https://echarts.apache.org/)

## 安装

- Step 1: 从 GitHub 上拉取仓库

```bash
cd your-blog/themes
git clone https://github.com/xbmlz/hexo-theme-fengye.git themes/fengye
```

- Step 2: 在 `_config.yml` 将 `theme` 改成 `fengye`.

```diff
_config.yml
- theme: some-theme
+ theme: fengye
```

## 配置

```yaml
# Header
nav:
  Home: /index  # 不会渲染 `source/index.md`
  Posts: /archives
  Categories: /category
  Tags: /tag
  Publications: /publications  # 渲染 `source/about.md`
  "About Me": /about  # 渲染 `source/about.md`

email: "chenyingfa1999@qq.com"

# favicon
favicon: /favicon.ico

# logo
logo: /images/logo.svg

# links
links:
  Github: https://github.com/xbmlz
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


