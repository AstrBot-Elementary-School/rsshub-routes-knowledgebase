# e 公司 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `egsea`
- Namespace Name: `e 公司`
- Route Path: `/egsea/flash`
- Route Name: `快讯`
- Example: `/egsea/flash`
- URL: `egsea.com/news/flash`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `hillerliao`
- Source Location: `flash.ts`
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
  - `egsea.com/news/flash`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/egsea/flash",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "flash.ts",
  "maintainers": [
    "hillerliao"
  ],
  "name": "快讯",
  "parameters": {},
  "path": "/flash",
  "radar": [
    {
      "source": [
        "egsea.com/news/flash"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "快讯 - e 公司 - Powered by RSSHub",
      "errorAt": "2026-08-17T06:42:47.466Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://www.egsea.com/news/flash-list?per-page=30\": <no response> fetch failed (Connect Timeout Error (attempted address: www.egsea.com:443, timeout: 10000ms))\n",
      "id": "71834563973302272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.egsea.com/news/flash",
      "title": "快讯 - e 公司",
      "type": "feed",
      "url": "rsshub://egsea/flash"
    }
  ],
  "url": "egsea.com/news/flash"
}
```
