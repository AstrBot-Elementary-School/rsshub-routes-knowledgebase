# 财新博客 - 最新文章

## Coverage
`index-only`

## Route
- Namespace: `caixin`
- Namespace Name: `财新博客`
- Route Path: `/caixin/latest`
- Route Name: `最新文章`
- Example: `/caixin/latest`
- URL: `caixin.com/`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `tpnonthealps`
- Source Location: `latest.ts`
- Source Module: `_None_`

## Description
说明：此 RSS feed 会自动抓取财新网的最新文章，但不包含 FM 及视频内容。订阅用户可根据文档设置环境变量后，在 url 传入`fulltext=`以解锁全文。

## Parameters
_None_


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
  - `caixin.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "description": "说明：此 RSS feed 会自动抓取财新网的最新文章，但不包含 FM 及视频内容。订阅用户可根据文档设置环境变量后，在 url 传入`fulltext=`以解锁全文。",
  "example": "/caixin/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13964,
  "location": "latest.ts",
  "maintainers": [
    "tpnonthealps"
  ],
  "name": "最新文章",
  "parameters": {},
  "path": "/latest",
  "radar": [
    {
      "source": [
        "caixin.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "财新网 - 最新文章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41443203209057309",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.caixin.com/",
      "title": "财新网 - 最新文章",
      "type": "feed",
      "url": "rsshub://caixin/latest"
    }
  ],
  "url": "caixin.com/",
  "view": 0
}
```
