# 起点 - 限时免费

## Coverage
`index-only`

## Route
- Namespace: `qidian`
- Namespace Name: `起点`
- Route Path: `/qidian/free/:type?`
- Route Name: `限时免费`
- Example: `/qidian/free`
- URL: `www.qidian.com/free`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `LogicJake, pseudoyu`
- Source Location: `free.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 默认不填为起点中文网，填 mm 为起点女生网


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
  - `www.qidian.com/free`
- `target`: `/free`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/qidian/free",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "free.ts",
  "maintainers": [
    "LogicJake",
    "pseudoyu"
  ],
  "name": "限时免费",
  "parameters": {
    "type": "默认不填为起点中文网，填 mm 为起点女生网"
  },
  "path": "/free/:type?",
  "radar": [
    {
      "source": [
        "www.qidian.com/free"
      ],
      "target": "/free"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "限时免费-起点中文网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "202693934180520960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qidian.com/free",
      "title": "起点中文网",
      "type": "feed",
      "url": "rsshub://qidian/free"
    }
  ],
  "url": "www.qidian.com/free"
}
```
