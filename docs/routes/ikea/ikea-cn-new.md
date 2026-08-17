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
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "当季新品推荐 - Powered by RSSHub",
      "errorAt": "2025-09-15T03:51:42.607Z",
      "errorMessage": "[POST] \"https://srv-mp.app.ikea.cn/content/search/products/advanced?keyword=%E6%96%B0%E5%93%81&moreToken\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 60.200.32.47:443, 60.200.32.44:443, 60.200.32.43:443, 60.200.32.46:443, 60.200.32.45:443, 60.200.32.50:443, 60.200.32.48:443, 60.200.32.49:443, timeout: 10000ms))\n",
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
