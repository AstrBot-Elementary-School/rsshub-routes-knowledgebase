# Anytxt Searcher - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `anytxt`
- Namespace Name: `Anytxt Searcher`
- Route Path: `/anytxt/release-notes`
- Route Name: `Release Notes`
- Example: `/anytxt/release-notes`
- URL: `anytxt.net`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `release-notes.ts`
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
  - `anytxt.net`
- `target`: `/anytxt/release-notes`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/anytxt/release-notes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 5,
  "location": "release-notes.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Release Notes",
  "path": "/release-notes",
  "radar": [
    {
      "source": [
        "anytxt.net"
      ],
      "target": "/anytxt/release-notes"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ 'https://anytxt.net/download/' ] to not include 'https://anytxt.net/download/'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Download | Anytxt Searcher - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "139875983124994048",
      "image": "https://anytxt.net/wp-content/uploads/2019/11/Anytxt-searcher-logo.png",
      "ownerUserId": null,
      "siteUrl": "https://anytxt.net/download/",
      "title": "Download | Anytxt Searcher",
      "type": "feed",
      "url": "rsshub://anytxt/release-notes"
    }
  ],
  "url": "anytxt.net",
  "view": 0
}
```
