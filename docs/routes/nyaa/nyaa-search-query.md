# Nyaa - Search Result

## Coverage
`index-only`

## Route
- Namespace: `nyaa`
- Namespace Name: `Nyaa`
- Route Path: `/nyaa/search/:query?`
- Route Name: `Search Result`
- Example: `/nyaa/search/psycho-pass`
- URL: `nyaa.si`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `LandonLi, noname1776, camera-2018, Q16KBreak`
- Source Location: `main.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `query`: Search keyword


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/nyaa/search/psycho-pass",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "main.ts",
  "maintainers": [
    "LandonLi",
    "noname1776",
    "camera-2018",
    "Q16KBreak"
  ],
  "name": "Search Result",
  "parameters": {
    "query": "Search keyword"
  },
  "path": [
    "/search/:query?",
    "/user/:username?",
    "/user/:username/search/:query?",
    "/sukebei/search/:query?",
    "/sukebei/user/:username?",
    "/sukebei/user/:username/search/:query?"
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "RSS Feed for Home - Powered by RSSHub",
      "errorAt": "2026-06-16T09:30:22.242Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 162739855683731456",
      "id": "162739855683731456",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nyaa.si/",
      "title": "Nyaa - Home - Torrent File RSS",
      "type": "feed",
      "url": "rsshub://nyaa/search"
    },
    {
      "description": "RSS Feed for \"psycho-pass\" - Powered by RSSHub",
      "errorAt": "2025-11-16T14:11:30.450Z",
      "errorMessage": "Non-whitespace before first tag.\nLine: 0\nColumn: 1\nChar: \u001f\n",
      "id": "67176366111133727",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nyaa.si/?q=psycho-pass",
      "title": "Nyaa - \"psycho-pass\" - Torrent File RSS",
      "type": "feed",
      "url": "rsshub://nyaa/search/psycho-pass"
    }
  ]
}
```
