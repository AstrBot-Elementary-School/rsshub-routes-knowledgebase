# 中国国家应急广播 - 应急新闻

## Coverage
`index-only`

## Route
- Namespace: `cneb`
- Namespace Name: `中国国家应急广播`
- Route Path: `/cneb/yjxw/:category?`
- Route Name: `应急新闻`
- Example: `/cneb/yjxw`
- URL: `cneb.gov.cn`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `nczitzk`
- Source Location: `yjxw.ts`
- Source Module: `_None_`

## Description
| 全部 | 国内新闻 | 国际新闻 |
| ---- | -------- | -------- |
|      | gnxw     | gjxw     |

## Parameters
- `category`: 分类，见下表，默认为全部


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
  - `cneb.gov.cn/yjxw/:category?`
  - `cneb.gov.cn/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "| 全部 | 国内新闻 | 国际新闻 |\n| ---- | -------- | -------- |\n|      | gnxw     | gjxw     |",
  "example": "/cneb/yjxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 18,
  "location": "yjxw.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "应急新闻",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/yjxw/:category?",
  "radar": [
    {
      "source": [
        "cneb.gov.cn/yjxw/:category?",
        "cneb.gov.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "国家应急广播 - 新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57295548899554304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cneb.gov.cn/yjxw",
      "title": "国家应急广播 - 新闻",
      "type": "feed",
      "url": "rsshub://cneb/yjxw"
    },
    {
      "description": "国家应急广播 - 国内新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73292547067243520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cneb.gov.cn/yjxw/gnxw",
      "title": "国家应急广播 - 国内新闻",
      "type": "feed",
      "url": "rsshub://cneb/yjxw/gnxw"
    }
  ]
}
```
