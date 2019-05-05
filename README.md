# Zen

A lean Hexo theme.

![Preview](https://i.loli.net/2019/05/05/5cce583fadaa3.png)

## Installation

### Install

```
git clone https://github.com/oif/hexo-theme-zen.git themes/zen
```

#### Dependency

- [hexo-renderer-less](https://www.npmjs.com/package/hexo-renderer-less)
- [hexo-symbols-count-time](https://www.npmjs.com/package/hexo-symbols-count-time)

```
npm install hexo-renderer-less --save
npm install hexo-symbols-count-time --save
```

### Update Theme

```
cd themes/zen
git pull
```

### Configuration

#### Highlight.js

To use Highlight.js have to disable Hexo code highlight in `_config.yml`

```
highlight:
  enable: false
  line_number: false
  auto_detect: false
  tab_replace:
```

#### Reading Time

Integrate with Reading Time please add and adjust those config in `_config.yml`

```
symbols_count_time:
  symbols: true
  time: true
  total_symbols: true
  total_time: true
  exclude_codeblock: false
  awl: 2
  wpm: 200
  suffix: mins.
```

For more details about those parameters see [Usage](https://github.com/theme-next/hexo-symbols-count-time#usage)


#### Theme

Set `theme` to `zen` in `_config.yml` to enable Zen theme

## Thanks

- [BootCDN](https://www.bootcdn.cn/): CSS/JS Lib
- [LUG@USTC](https://lug.ustc.edu.cn): Google Fonts Mirror

