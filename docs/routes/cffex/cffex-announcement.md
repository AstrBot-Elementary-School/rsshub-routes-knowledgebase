# 中国金融期货交易所 - 交易所公告

## Coverage
`index-only`

## Route
- Namespace: `cffex`
- Namespace Name: `中国金融期货交易所`
- Route Path: `/cffex/announcement`
- Route Name: `交易所公告`
- Example: `/cffex/announcement`
- URL: `www.cffex.com.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ChenXiangcheng1`
- Source Location: `announcement.ts`
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
  - `cffex.com.cn`
- `target`: `/announcement`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "",
  "example": "/cffex/announcement",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "announcement.ts",
  "maintainers": [
    "ChenXiangcheng1"
  ],
  "name": "交易所公告",
  "parameters": {},
  "path": "/announcement",
  "radar": [
    {
      "source": [
        "cffex.com.cn"
      ],
      "target": "/announcement"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "中国金融期货交易所 - 交易所公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72147630295105536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cffex.com.cn/jystz",
      "title": "中国金融期货交易所 - 交易所公告",
      "type": "feed",
      "url": "rsshub://cffex/announcement"
    }
  ],
  "url": "www.cffex.com.cn"
}
```
