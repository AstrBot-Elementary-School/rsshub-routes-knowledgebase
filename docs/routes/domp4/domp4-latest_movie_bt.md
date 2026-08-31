# DoMP4 影视 - 最近更新的电源BT列表

## Coverage
`index-only`

## Route
- Namespace: `domp4`
- Namespace Name: `DoMP4 影视`
- Route Path: `/domp4/latest_movie_bt`
- Route Name: `最近更新的电源BT列表`
- Example: `/domp4/latest_movie_bt`
- URL: `www.xlmp4.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `xianghuawe, pseudoyu`
- Source Location: `latest-movie-bt.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.xlmp4.com/`
  - `www.xlmp4.com/custom/update.html`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/domp4/latest_movie_bt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 34,
  "location": "latest-movie-bt.ts",
  "maintainers": [
    "xianghuawe",
    "pseudoyu"
  ],
  "name": "最近更新的电源BT列表",
  "parameters": {},
  "path": "/latest_movie_bt",
  "radar": [
    {
      "source": [
        "www.xlmp4.com/",
        "www.xlmp4.com/custom/update.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "domp4电影 - Powered by RSSHub",
      "errorAt": "2025-05-15T15:20:46.121Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "66073912567524352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.xlmp4.com/custom/update.html",
      "title": "domp4电影",
      "type": "feed",
      "url": "rsshub://domp4/latest_movie_bt"
    }
  ],
  "url": "www.xlmp4.com/"
}
```
