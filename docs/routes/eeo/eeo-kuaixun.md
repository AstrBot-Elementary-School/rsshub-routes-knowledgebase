# 经济观察网 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `eeo`
- Namespace Name: `经济观察网`
- Route Path: `/eeo/kuaixun`
- Route Name: `快讯`
- Example: `/eeo/kuaixun`
- URL: `www.eeo.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `kuaixun.ts`
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
  - `www.eeo.com.cn/kuaixun/`
- `target`: `/kuaixun`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/eeo/kuaixun",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 12,
  "location": "kuaixun.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "快讯",
  "path": "/kuaixun",
  "radar": [
    {
      "source": [
        "www.eeo.com.cn/kuaixun/"
      ],
      "target": "/kuaixun"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "快讯_经济观察网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "194919237802284032",
      "image": "https://img.eeo.com.cn/2024/images/logo.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.eeo.com.cn/kuaixun/",
      "title": "快讯_经济观察网",
      "type": "feed",
      "url": "rsshub://eeo/kuaixun"
    }
  ],
  "url": "www.eeo.com.cn",
  "view": 0
}
```
