# TCTMD - Conference News

## Coverage
`index-only`

## Route
- Namespace: `tctmd`
- Namespace Name: `TCTMD`
- Route Path: `/tctmd/conference-news`
- Route Name: `Conference News`
- Example: `/tctmd/conference-news`
- URL: `www.tctmd.com/news/conference-news`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `ChuYinan2023`
- Source Location: `conference-news.ts`
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
  - `www.tctmd.com/news/conference-news`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/tctmd/conference-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "conference-news.ts",
  "maintainers": [
    "ChuYinan2023"
  ],
  "name": "Conference News",
  "parameters": {},
  "path": "/conference-news",
  "radar": [
    {
      "source": [
        "www.tctmd.com/news/conference-news"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Latest conference news coverage from TCTMD, the leading source for interventional cardiology news - Powered by RSSHub",
      "errorAt": "2026-08-10T06:13:42.591Z",
      "errorMessage": "[GET] \"https://www.tctmd.com/search?keyword=&f%5B0%5D=news_subtype%3AConference%20News&f%5B1%5D=type%3Anews\": 403 Forbidden\n",
      "id": "244181614864227328",
      "image": "https://www.tctmd.com/themes/tctmd/logo.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.tctmd.com/news/conference-news",
      "title": "TCTMD - Conference News",
      "type": "feed",
      "url": "rsshub://tctmd/conference-news"
    }
  ],
  "url": "www.tctmd.com/news/conference-news"
}
```
