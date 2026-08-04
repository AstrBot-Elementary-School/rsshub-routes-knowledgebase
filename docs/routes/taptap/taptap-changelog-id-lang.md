# TapTap - 游戏更新

## Coverage
`index-only`

## Route
- Namespace: `taptap`
- Namespace Name: `TapTap`
- Route Path: `/taptap/changelog/:id/:lang?`
- Route Name: `游戏更新`
- Example: `/taptap/changelog/60809/en_US`
- URL: `www.taptap.io`
- Language: `_None_`
- Categories: `game`
- Maintainers: `hoilc, ETiV`
- Source Location: `changelog-cn.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 游戏 ID，游戏主页 URL 中获取
- `lang`: 语言，默认使用 `zh_CN`，亦可使用 `en_US`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.taptap.cn/app/:id`
- `target`: `/changelog/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/taptap/changelog/60809/en_US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "changelog-cn.ts",
  "maintainers": [
    "hoilc",
    "ETiV"
  ],
  "name": "游戏更新",
  "parameters": {
    "id": "游戏 ID，游戏主页 URL 中获取",
    "lang": "语言，默认使用 `zh_CN`，亦可使用 `en_US`"
  },
  "path": "/changelog/:id/:lang?",
  "radar": [
    {
      "source": [
        "www.taptap.cn/app/:id"
      ],
      "target": "/changelog/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "暗区突围 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "122918327659466752",
      "image": "https://img-tc.tapimg.com/market/images/f4f7db399fdbb9b0c0dc6e5f7256ab1d.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.taptap.cn/app/221322",
      "title": "TapTap 更新记录 暗区突围",
      "type": "feed",
      "url": "rsshub://taptap/changelog/221322"
    },
    {
      "description": "燕云十六声 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "203995001057763328",
      "image": "https://img-tc.tapimg.com/market/images/515c6583cd5cb05f2f343e8b581df575.png",
      "ownerUserId": null,
      "siteUrl": "https://www.taptap.cn/app/239372",
      "title": "TapTap 更新记录 燕云十六声",
      "type": "feed",
      "url": "rsshub://taptap/changelog/239372"
    }
  ]
}
```
