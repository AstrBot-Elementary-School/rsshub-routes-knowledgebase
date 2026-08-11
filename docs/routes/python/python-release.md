# Python - Active Python Releases

## Coverage
`index-only`

## Route
- Namespace: `python`
- Namespace Name: `Python`
- Route Path: `/python/release`
- Route Name: `Active Python Releases`
- Example: `/python/release`
- URL: `www.python.org`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `release.ts`
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
  - `www.python.org`
  - `www.python.org/downloads`
- `target`: `/release`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/python/release",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 82,
  "location": "release.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Active Python Releases",
  "path": "/release",
  "radar": [
    {
      "source": [
        "www.python.org",
        "www.python.org/downloads"
      ],
      "target": "/release"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -4574064416 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "The official home of the Python Programming Language - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160122574224355328",
      "image": "https://www.python.org/static/opengraph-icon-200x200.png",
      "ownerUserId": null,
      "siteUrl": "https://www.python.org/downloads",
      "title": "Active Python releases",
      "type": "feed",
      "url": "rsshub://python/release"
    }
  ],
  "url": "www.python.org",
  "view": 0
}
```
