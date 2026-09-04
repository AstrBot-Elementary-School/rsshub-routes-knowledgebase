# 知乎 - 知乎日报

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/daily`
- Route Name: `知乎日报`
- Example: `/zhihu/daily`
- URL: `daily.zhihu.com/*`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DHPO, pseudoyu`
- Source Location: `daily.ts`
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

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/daily",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 838,
  "location": "daily.ts",
  "maintainers": [
    "DHPO",
    "pseudoyu"
  ],
  "name": "知乎日报",
  "parameters": {},
  "path": "/daily",
  "radar": [
    {
      "source": [
        "daily.zhihu.com/*"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "每天3次，每次7分钟 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73575434596858887",
      "image": "http://static.daily.zhihu.com/img/new_home_v3/mobile_top_logo.png",
      "ownerUserId": null,
      "siteUrl": "https://daily.zhihu.com/",
      "title": "知乎日报",
      "type": "feed",
      "url": "rsshub://zhihu/daily"
    }
  ],
  "url": "daily.zhihu.com/*"
}
```
