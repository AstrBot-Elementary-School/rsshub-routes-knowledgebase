# 知乎 - 知乎想法 - 24 小时新闻汇总

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/pin/daily`
- Route Name: `知乎想法 - 24 小时新闻汇总`
- Example: `/zhihu/pin/daily`
- URL: `daily.zhihu.com/*`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `pin/daily.ts`
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
  - `daily.zhihu.com/*`
- `target`: `/daily`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/pin/daily",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 247,
  "location": "pin/daily.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "知乎想法 - 24 小时新闻汇总",
  "parameters": {},
  "path": "/pin/daily",
  "radar": [
    {
      "source": [
        "daily.zhihu.com/*"
      ],
      "target": "/daily"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "汇集每天的社会大事、行业资讯，让你用最简单的方式获得想法里的新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59476073652518935",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/pin/special/972884951192113152",
      "title": "知乎想法-24小时新闻汇总",
      "type": "feed",
      "url": "rsshub://zhihu/pin/daily"
    }
  ],
  "url": "daily.zhihu.com/*"
}
```
