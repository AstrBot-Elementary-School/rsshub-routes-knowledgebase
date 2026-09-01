# 财新博客 - 财新数据通

## Coverage
`index-only`

## Route
- Namespace: `caixin`
- Namespace Name: `财新博客`
- Route Path: `/caixin/database`
- Route Name: `财新数据通`
- Example: `/caixin/database`
- URL: `k.caixin.com/web`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `database.ts`
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
  - `k.caixin.com/web`
  - `k.caixin.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/caixin/database",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 95,
  "location": "database.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "财新数据通",
  "parameters": {},
  "path": "/database",
  "radar": [
    {
      "source": [
        "k.caixin.com/web",
        "k.caixin.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "财新数据通 - 专享资讯 - Powered by RSSHub",
      "errorAt": "2026-08-31T00:31:21.921Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://database.caixin.com/news/\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 172.96.121.42:443, timeout: 10000ms))\n",
      "id": "59040048063587328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://database.caixin.com/news/",
      "title": "财新数据通 - 专享资讯",
      "type": "feed",
      "url": "rsshub://caixin/database"
    }
  ],
  "url": "k.caixin.com/web"
}
```
