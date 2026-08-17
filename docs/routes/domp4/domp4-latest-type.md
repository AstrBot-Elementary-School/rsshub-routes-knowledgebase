# DoMP4 影视 - 最近更新

## Coverage
`index-only`

## Route
- Namespace: `domp4`
- Namespace Name: `DoMP4 影视`
- Route Path: `/domp4/latest/:type?`
- Route Name: `最近更新`
- Example: `/domp4/latest/vod`
- URL: `www.xlmp4.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `savokiss, pseudoyu`
- Source Location: `latest.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: `vod` 代表电影，`tv` 代表电视剧，默认 vod


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
  - `www.xlmp4.com/`
  - `www.xlmp4.com/custom/update.html`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/domp4/latest/vod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 84,
  "location": "latest.ts",
  "maintainers": [
    "savokiss",
    "pseudoyu"
  ],
  "name": "最近更新",
  "parameters": {
    "type": "`vod` 代表电影，`tv` 代表电视剧，默认 vod"
  },
  "path": "/latest/:type?",
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
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "domp4电影 - Powered by RSSHub",
      "errorAt": "2025-05-15T16:33:12.170Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "59547099087379456",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.xlmp4.com/custom/update.html",
      "title": "domp4电影",
      "type": "feed",
      "url": "rsshub://domp4/latest/vod"
    },
    {
      "description": "domp4电影 - Powered by RSSHub",
      "errorAt": "2025-05-15T17:19:35.955Z",
      "errorMessage": "Failed to fetch\n",
      "id": "69928302166378496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.xlmp4.com/custom/update.html",
      "title": "domp4电影",
      "type": "feed",
      "url": "rsshub://domp4/latest"
    }
  ],
  "url": "www.xlmp4.com/"
}
```
