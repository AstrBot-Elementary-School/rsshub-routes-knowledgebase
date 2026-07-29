# 经济观察网 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `eeo`
- Namespace Name: `经济观察网`
- Route Path: `/eeo/kuaixun`
- Route Name: `快讯`
- Example: `/eeo/kuaixun`
- URL: `www.eeo.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `kuaixun.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.eeo.com.cn/kuaixun/`
- `target`: `/kuaixun`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/eeo/kuaixun",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 12,
  "location": "kuaixun.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "快讯",
  "path": "/kuaixun",
  "radar": [
    {
      "source": [
        "www.eeo.com.cn/kuaixun/"
      ],
      "target": "/kuaixun"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "快讯_经济观察网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "194919237802284032",
      "image": "https://img.eeo.com.cn/2024/images/logo.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.eeo.com.cn/kuaixun/",
      "title": "快讯_经济观察网",
      "type": "feed",
      "url": "rsshub://eeo/kuaixun"
    }
  ],
  "url": "www.eeo.com.cn",
  "view": 0
}
```
