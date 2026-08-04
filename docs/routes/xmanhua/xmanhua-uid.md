# X 漫画 - 最新动态

## Coverage
`index-only`

## Route
- Namespace: `xmanhua`
- Namespace Name: `X 漫画`
- Route Path: `/xmanhua/:uid`
- Route Name: `最新动态`
- Example: `/xmanhua/73xm`
- URL: `xmanhua.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `Ye11`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 漫画 id,在浏览器中可见，例如鬼灭之刃对应的 id 为 `73xm`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `xmanhua.com/:uid`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/xmanhua/73xm",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 31,
  "location": "index.ts",
  "maintainers": [
    "Ye11"
  ],
  "name": "最新动态",
  "parameters": {
    "uid": "漫画 id,在浏览器中可见，例如鬼灭之刃对应的 id 为 `73xm`"
  },
  "path": "/:uid",
  "radar": [
    {
      "source": [
        "xmanhua.com/:uid"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "已完结 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59867401847046144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xmanhua.com/73xm",
      "title": "x漫画 鬼滅之刃",
      "type": "feed",
      "url": "rsshub://xmanhua/73xm"
    },
    {
      "description": "连载中 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82662234603799552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xmanhua.com/38xm",
      "title": "x漫画 一拳超人",
      "type": "feed",
      "url": "rsshub://xmanhua/38xm"
    }
  ]
}
```
