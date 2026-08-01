# IKEA - 中国 - 当季新品推荐

## Coverage
`index-only`

## Route
- Namespace: `ikea`
- Namespace Name: `IKEA`
- Route Path: `/ikea/cn/new`
- Route Name: `中国 - 当季新品推荐`
- Example: `/ikea/cn/new`
- URL: `ikea.cn/cn/zh/new/`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `jzhangdev`
- Source Location: `cn/new.ts`
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
  - `ikea.cn/cn/zh/new/`
  - `ikea.cn/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/ikea/cn/new",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 31,
  "location": "cn/new.ts",
  "maintainers": [
    "jzhangdev"
  ],
  "name": "中国 - 当季新品推荐",
  "parameters": {},
  "path": "/cn/new",
  "radar": [
    {
      "source": [
        "ikea.cn/cn/zh/new/",
        "ikea.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "当季新品推荐 - Powered by RSSHub",
      "errorAt": "2025-09-15T03:51:42.607Z",
      "errorMessage": "Failed to fetch\n",
      "id": "66834743977124868",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ikea.cn/cn/zh/new/",
      "title": "IKEA 宜家 - 当季新品推荐",
      "type": "feed",
      "url": "rsshub://ikea/cn/new"
    }
  ],
  "url": "ikea.cn/cn/zh/new/"
}
```
