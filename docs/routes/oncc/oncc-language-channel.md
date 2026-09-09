# 东网 - 即時新聞

## Coverage
`index-only`

## Route
- Namespace: `oncc`
- Namespace Name: `东网`
- Route Path: `/oncc/:language/:channel?`
- Route Name: `即時新聞`
- Example: `/oncc/zh-hant/news`
- URL: `hk.on.cc`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Fatpandac`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
频道参数可以从官网的地址中获取，如：

`https://hk.on.cc/hk/finance/index_cn.html` 对应 `/oncc/zh-hans/finance`

`https://hk.on.cc/hk/finance/index.html` 对应 `/oncc/zh-hant/finance`

## Parameters
- `language`: `zh-hans` 为简体，`zh-hant` 为繁体
- `channel`: 频道，默认为港澳


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "频道参数可以从官网的地址中获取，如：\n\n`https://hk.on.cc/hk/finance/index_cn.html` 对应 `/oncc/zh-hans/finance`\n\n`https://hk.on.cc/hk/finance/index.html` 对应 `/oncc/zh-hant/finance`",
  "example": "/oncc/zh-hant/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 279,
  "location": "index.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "即時新聞",
  "parameters": {
    "channel": "频道，默认为港澳",
    "language": "`zh-hans` 为简体，`zh-hant` 为繁体"
  },
  "path": "/:language/:channel?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "東網 - 港澳 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61348617925421056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hk.on.cc/hk/news/index.html",
      "title": "東網 - 港澳",
      "type": "feed",
      "url": "rsshub://oncc/zh-hant/news"
    },
    {
      "description": "東網 - 港澳 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74060845450725376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hk.on.cc/hk/news/index_cn.html",
      "title": "東網 - 港澳",
      "type": "feed",
      "url": "rsshub://oncc/zh-hans/news"
    }
  ]
}
```
