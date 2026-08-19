# 知乎 - 知乎热榜

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/hot/:category?`
- Route Name: `知乎热榜`
- Example: `/zhihu/hot`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `nczitzk, pseudoyu, DIYgod`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/zhihu/hot",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15688,
  "location": "hot.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu",
    "DIYgod"
  ],
  "name": "知乎热榜",
  "path": "/hot/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "知乎热榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41358761177015296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/hot",
      "title": "知乎热榜",
      "type": "feed",
      "url": "rsshub://zhihu/hot"
    }
  ],
  "view": 0
}
```
