# 北京天文馆 - 每日一图

## Coverage
`index-only`

## Route
- Namespace: `bjp`
- Namespace Name: `北京天文馆`
- Route Path: `/bjp/apod`
- Route Name: `每日一图`
- Example: `/bjp/apod`
- URL: `bjp.org.cn/APOD/today.shtml`
- Language: `_None_`
- Categories: `picture, popular`
- Maintainers: `HenryQW`
- Source Location: `apod.ts`
- Source Module: `_None_`

## Description
_None_

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
  - `bjp.org.cn/APOD/today.shtml`
  - `bjp.org.cn/APOD/list.shtml`
  - `bjp.org.cn/`

## Raw JSON
```json
{
  "categories": [
    "picture",
    "popular"
  ],
  "example": "/bjp/apod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4279,
  "location": "apod.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "每日一图",
  "parameters": {},
  "path": "/apod",
  "radar": [
    {
      "source": [
        "bjp.org.cn/APOD/today.shtml",
        "bjp.org.cn/APOD/list.shtml",
        "bjp.org.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "探索宇宙！每天发布一张迷人宇宙的影像，以及由专业天文学家撰写的简要说明。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55304291112288259",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bjp.org.cn/APOD/list.shtml",
      "title": "每日一图-北京天文馆",
      "type": "feed",
      "url": "rsshub://bjp/apod"
    }
  ],
  "url": "bjp.org.cn/APOD/today.shtml",
  "view": 2
}
```
