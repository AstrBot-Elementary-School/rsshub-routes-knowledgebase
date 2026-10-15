# 歪脑 - 读

## Coverage
`index-only`

## Route
- Namespace: `wainao`
- Namespace Name: `歪脑`
- Route Path: `/wainao/wainao-reads`
- Route Name: `读`
- Example: `/wainao/wainao-reads`
- URL: `www.wainao.me`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `lucky13820`
- Source Location: `wainao-reads.ts`
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
  - `www.wainao.me`
  - `www.wainao.me/wainao-reads`
- `target`: `/wainao-reads`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/wainao/wainao-reads",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 57,
  "location": "wainao-reads.ts",
  "maintainers": [
    "lucky13820"
  ],
  "name": "读",
  "path": "/wainao-reads",
  "radar": [
    {
      "source": [
        "www.wainao.me",
        "www.wainao.me/wainao-reads"
      ],
      "target": "/wainao-reads"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "歪脑读 - 歪脑 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "109801824683778048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.wainao.me/",
      "title": "歪脑读 - 歪脑",
      "type": "feed",
      "url": "rsshub://wainao/wainao-reads"
    }
  ],
  "url": "www.wainao.me"
}
```
