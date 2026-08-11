# 知乎 - 知乎想法热榜

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/pin/hotlist`
- Route Name: `知乎想法热榜`
- Example: `/zhihu/pin/hotlist`
- URL: `www.zhihu.com/zhihu/bookstore/newest`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `pin/hotlist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/zhihu/bookstore/newest`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/pin/hotlist",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 47,
  "location": "pin/hotlist.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "知乎想法热榜",
  "parameters": {},
  "path": "/pin/hotlist",
  "radar": [
    {
      "source": [
        "www.zhihu.com/zhihu/bookstore/newest"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "整点更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42522522216960001",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/",
      "title": "知乎想法热榜",
      "type": "feed",
      "url": "rsshub://zhihu/pin/hotlist"
    }
  ],
  "url": "www.zhihu.com/zhihu/bookstore/newest"
}
```
