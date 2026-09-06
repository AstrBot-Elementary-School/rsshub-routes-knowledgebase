# 上海市人民政府 - 发展和改革委员会

## Coverage
`index-only`

## Route
- Namespace: `gov/sh`
- Namespace Name: `上海市人民政府`
- Route Path: `/gov/sh/fgw/:category{.+}?`
- Route Name: `发展和改革委员会`
- Example: `/gov/sh/fgw/fgw_zxxxgk`
- URL: `fgw.sh.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `fgw/index.tsx`
- Source Module: `_None_`

## Description
::: tip
若订阅 [最新信息公开](https://fgw.sh.gov.cn/fgw_zxxxgk/index.html)，网址为 `https://fgw.sh.gov.cn/fgw_zxxxgk/index.html`。截取 `https://fgw.sh.gov.cn/` 到末尾 `/index.html` 的部分 `fgw_zxxxgk` 作为参数填入，此时路由为 [`/gov/sh/fgw/fgw_zxxxgk`](https://rsshub.app/gov/sh/fgw/fgw_zxxxgk)。
:::

| 最新信息公开 | 要闻动态    |
| ------------ | ----------- |
| fgw\_zxxxgk  | fgw\_fzggdt |

## Parameters
- `category`: 分类，默认为 `fgw_zxxxgk`，即最新信息公开，可在对应分类页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `fgw.sh.gov.cn/:category`
### Rule 2
- `title`: `最新信息公开`
- `source`:
  - `fgw.sh.gov.cn/fgw_zxxxgk/index.html`
- `target`: `/fgw/fgw_zxxxgk`
### Rule 3
- `title`: `要闻动态`
- `source`:
  - `fgw.sh.gov.cn/fgw_fzggdt/index.html`
- `target`: `/fgw/fgw_fzggdt`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n若订阅 [最新信息公开](https://fgw.sh.gov.cn/fgw_zxxxgk/index.html)，网址为 `https://fgw.sh.gov.cn/fgw_zxxxgk/index.html`。截取 `https://fgw.sh.gov.cn/` 到末尾 `/index.html` 的部分 `fgw_zxxxgk` 作为参数填入，此时路由为 [`/gov/sh/fgw/fgw_zxxxgk`](https://rsshub.app/gov/sh/fgw/fgw_zxxxgk)。\n:::\n\n| 最新信息公开 | 要闻动态    |\n| ------------ | ----------- |\n| fgw\\_zxxxgk  | fgw\\_fzggdt |",
  "example": "/gov/sh/fgw/fgw_zxxxgk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 13,
  "location": "fgw/index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "发展和改革委员会",
  "parameters": {
    "category": "分类，默认为 `fgw_zxxxgk`，即最新信息公开，可在对应分类页 URL 中找到"
  },
  "path": "/fgw/:category{.+}?",
  "radar": [
    {
      "source": [
        "fgw.sh.gov.cn/:category"
      ]
    },
    {
      "source": [
        "fgw.sh.gov.cn/fgw_zxxxgk/index.html"
      ],
      "target": "/fgw/fgw_zxxxgk",
      "title": "最新信息公开"
    },
    {
      "source": [
        "fgw.sh.gov.cn/fgw_fzggdt/index.html"
      ],
      "target": "/fgw/fgw_fzggdt",
      "title": "要闻动态"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "最新政策 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66776163809391616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fgw.sh.gov.cn/fgw_zxxxgk/index.html",
      "title": "上海市发展和改革委员会 - 最新政策",
      "type": "feed",
      "url": "rsshub://gov/sh/fgw/fgw_zxxxgk"
    }
  ],
  "url": "fgw.sh.gov.cn"
}
```
