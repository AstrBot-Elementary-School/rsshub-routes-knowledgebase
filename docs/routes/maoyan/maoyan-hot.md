# 猫眼电影 - 正在热映

## Coverage
`index-only`

## Route
- Namespace: `maoyan`
- Namespace Name: `猫眼电影`
- Route Path: `/maoyan/hot`
- Route Name: `正在热映`
- Example: `/maoyan/hot`
- URL: `maoyan.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `JackyST0`
- Source Location: `hot.ts`
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
  - `www.maoyan.com/films?showType=1`
- `target`: `/hot`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/maoyan/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15,
  "location": "hot.ts",
  "maintainers": [
    "JackyST0"
  ],
  "name": "正在热映",
  "parameters": {},
  "path": "/hot",
  "radar": [
    {
      "source": [
        "www.maoyan.com/films?showType=1"
      ],
      "target": "/hot"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "猫眼电影正在热映列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "148757739569766403",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.maoyan.com/films?showType=1",
      "title": "猫眼电影 - 正在热映",
      "type": "feed",
      "url": "rsshub://maoyan/hot"
    }
  ]
}
```
