# 知乎 - 知乎日报 - 合集

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/daily/section/:sectionId`
- Route Name: `知乎日报 - 合集`
- Example: `/zhihu/daily/section/2`
- URL: `daily.zhihu.com/*`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `ccbikai`
- Source Location: `daily-section.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `sectionId`: 合集 id，可在 https://news-at.zhihu.com/api/7/sections 找到


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
  "example": "/zhihu/daily/section/2",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 51,
  "location": "daily-section.ts",
  "maintainers": [
    "ccbikai"
  ],
  "name": "知乎日报 - 合集",
  "parameters": {
    "sectionId": "合集 id，可在 https://news-at.zhihu.com/api/7/sections 找到"
  },
  "path": "/daily/section/:sectionId",
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
      "description": "每天3次，每次7分钟 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58885675171745799",
      "image": "http://static.daily.zhihu.com/img/new_home_v3/mobile_top_logo.png",
      "ownerUserId": null,
      "siteUrl": "https://daily.zhihu.com/",
      "title": "瞎扯 - 知乎日报",
      "type": "feed",
      "url": "rsshub://zhihu/daily/section/2"
    }
  ],
  "url": "daily.zhihu.com/*"
}
```
