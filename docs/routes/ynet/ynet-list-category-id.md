# 北青网 - 列表

## Coverage
`index-only`

## Route
- Namespace: `ynet`
- Namespace Name: `北青网`
- Route Path: `/ynet/list/:category?/:id?`
- Route Name: `列表`
- Example: `/ynet/list/news/2121t76`
- URL: `ynet.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `list.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [北青快讯](https://news.ynet.com/list/2121t76.html)，其源网址为 `https://news.ynet.com/list/2121t76.html`，请参考该 URL 指定部分构成参数，此时路由为 [`/ynet/list/news/2121t76`](https://rsshub.app/ynet/list/news/2121t76)。
:::

## Parameters
- `category`: {"description": "分类，默认为 `news`，可在对应分类页 URL 中找到"}
- `id`: {"description": "列表 ID，可在对应列表页 URL 中找到"}


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
  - `ynet.com`
- `target`: `/list`
### Rule 2
- `source`:
  - `news.ynet.com/list/2121t76.html`
- `target`: `/list/news/2121t76`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n订阅 [北青快讯](https://news.ynet.com/list/2121t76.html)，其源网址为 `https://news.ynet.com/list/2121t76.html`，请参考该 URL 指定部分构成参数，此时路由为 [`/ynet/list/news/2121t76`](https://rsshub.app/ynet/list/news/2121t76)。\n:::",
  "example": "/ynet/list/news/2121t76",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "list.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "列表",
  "parameters": {
    "category": {
      "description": "分类，默认为 `news`，可在对应分类页 URL 中找到"
    },
    "id": {
      "description": "列表 ID，可在对应列表页 URL 中找到"
    }
  },
  "path": "/list/:category?/:id?",
  "radar": [
    {
      "source": [
        "ynet.com"
      ],
      "target": "/list"
    },
    {
      "source": [
        "news.ynet.com/list/2121t76.html"
      ],
      "target": "/list/news/2121t76"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "ynet.com",
  "view": 0
}
```
