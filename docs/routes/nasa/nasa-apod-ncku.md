# NASA - Cheng Kung University Mirror

## Coverage
`index-only`

## Route
- Namespace: `nasa`
- Namespace Name: `NASA`
- Route Path: `/nasa/apod-ncku`
- Route Name: `Cheng Kung University Mirror`
- Example: `/nasa/apod-ncku`
- URL: `sprite.phys.ncku.edu.tw/astrolab/mirrors/apod/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `nczitzk, williamgateszhao`
- Source Location: `apod-ncku.ts`
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
  - `sprite.phys.ncku.edu.tw/astrolab/mirrors/apod/*path`
  - `sprite.phys.ncku.edu.tw/astrolab/mirrors/apod`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/nasa/apod-ncku",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 35,
  "location": "apod-ncku.ts",
  "maintainers": [
    "nczitzk",
    "williamgateszhao"
  ],
  "name": "Cheng Kung University Mirror",
  "parameters": {},
  "path": "/apod-ncku",
  "radar": [
    {
      "source": [
        "sprite.phys.ncku.edu.tw/astrolab/mirrors/apod/*path",
        "sprite.phys.ncku.edu.tw/astrolab/mirrors/apod"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "NASA 每日一天文圖 (成大物理分站) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63858618178298972",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://sprite.phys.ncku.edu.tw/astrolab/mirrors/apod/archivepix.html",
      "title": "NASA 每日一天文圖 (成大物理分站)",
      "type": "feed",
      "url": "rsshub://nasa/apod-ncku"
    }
  ],
  "url": "sprite.phys.ncku.edu.tw/astrolab/mirrors/apod/"
}
```
