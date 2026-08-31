# Not a Tesla App - Tesla Software Updates

## Coverage
`index-only`

## Route
- Namespace: `notateslaapp`
- Namespace Name: `Not a Tesla App`
- Route Path: `/notateslaapp/ota`
- Route Name: `Tesla Software Updates`
- Example: `/notateslaapp/ota`
- URL: `notateslaapp.com/software-updates/history`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `mrbruce516`
- Source Location: `update.ts`
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
  - `notateslaapp.com/software-updates/history`
  - `notateslaapp.com/software-updates`
  - `notateslaapp.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/notateslaapp/ota",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "update.ts",
  "maintainers": [
    "mrbruce516"
  ],
  "name": "Tesla Software Updates",
  "parameters": {},
  "path": "/ota",
  "radar": [
    {
      "source": [
        "notateslaapp.com/software-updates/history",
        "notateslaapp.com/software-updates",
        "notateslaapp.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(23) ] to not include 'https://www.notateslaapp.com/software…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "特斯拉系统更新 - 最新发布 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66384857823758336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.notateslaapp.com/software-updates/history/",
      "title": "特斯拉系统更新",
      "type": "feed",
      "url": "rsshub://notateslaapp/ota"
    }
  ],
  "url": "notateslaapp.com/software-updates/history"
}
```
