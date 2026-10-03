# NASA - Cheng Kung University Mirror

## Coverage
`index-only`

## Route
- Namespace: `nasa`
- Namespace Name: `NASA`
- Route Path: `/nasa/apod-ncku`
- Route Name: `Cheng Kung University Mirror`
- Example: `/nasa/apod-ncku`
- URL: `apod.nasa.govundefined`
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
  - `apod.nasa.govundefined`

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
        "apod.nasa.govundefined"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "NASA 每日一天文圖 (成大物理分站) - Powered by RSSHub",
      "errorAt": "2026-09-30T06:20:50.111Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "63858618178298972",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://sprite.phys.ncku.edu.tw/astrolab/mirrors/apod/archivepix.html",
      "title": "NASA 每日一天文圖 (成大物理分站)",
      "type": "feed",
      "url": "rsshub://nasa/apod-ncku"
    }
  ],
  "url": "apod.nasa.govundefined"
}
```
