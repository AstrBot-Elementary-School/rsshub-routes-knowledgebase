# Cloudflare Status - Status

## Coverage
`index-only`

## Route
- Namespace: `cloudflarestatus`
- Namespace Name: `Cloudflare Status`
- Route Path: `/cloudflarestatus/`
- Route Name: `Status`
- Example: `/cloudflarestatus`
- URL: `www.cloudflarestatus.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
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
  - `www.cloudflarestatus.com`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/cloudflarestatus",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Status",
  "path": "/",
  "radar": [
    {
      "source": [
        "www.cloudflarestatus.com"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(26) ] to not include 'https://www.cloudflarestatus.com/inci…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.cloudflarestatus.com",
  "view": 5
}
```
