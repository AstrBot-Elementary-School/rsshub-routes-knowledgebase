# V2EX - 标签

## Coverage
`index-only`

## Route
- Namespace: `v2ex`
- Namespace Name: `V2EX`
- Route Path: `/v2ex/tab/:tabid`
- Route Name: `标签`
- Example: `/v2ex/tab/hot`
- URL: `v2ex.com`
- Language: `_None_`
- Categories: `bbs, popular`
- Maintainers: `liyefox`
- Source Location: `tab.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tabid`: tab标签ID,在 URL 可以找到


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
    "bbs",
    "popular"
  ],
  "example": "/v2ex/tab/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1396,
  "location": "tab.ts",
  "maintainers": [
    "liyefox"
  ],
  "name": "标签",
  "parameters": {
    "tabid": "tab标签ID,在 URL 可以找到"
  },
  "path": "/tab/:tabid",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "V2EX-tab-hot - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41707278446398464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://v2ex.com/?tab=hot",
      "title": "V2EX-hot",
      "type": "feed",
      "url": "rsshub://v2ex/tab/hot"
    },
    {
      "description": "V2EX-tab-apple - Powered by RSSHub",
      "errorAt": "2026-08-16T04:22:24.575Z",
      "errorMessage": "200 ",
      "id": "46752076079222784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://v2ex.com/?tab=apple",
      "title": "V2EX-apple",
      "type": "feed",
      "url": "rsshub://v2ex/tab/apple"
    }
  ],
  "view": 0
}
```
