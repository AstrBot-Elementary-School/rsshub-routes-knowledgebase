# 中国管理现代化研究会 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `camchina`
- Namespace Name: `中国管理现代化研究会`
- Route Path: `/camchina/:id?`
- Route Name: `栏目`
- Example: `/camchina`
- URL: `cste.org.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 新闻 | 通告栏 |
| ---- | ------ |
| 1    | 2      |

## Parameters
- `id`: 分类，见下表，默认为 1，即新闻


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
  - `cste.org.cn/categories/:id`
  - `cste.org.cn/`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| 新闻 | 通告栏 |\n| ---- | ------ |\n| 1    | 2      |",
  "example": "/camchina",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "id": "分类，见下表，默认为 1，即新闻"
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "cste.org.cn/categories/:id",
        "cste.org.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "中国管理现代化研究会 - 新 闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67194504414483456",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.camchina.org.cn/categories/1",
      "title": "中国管理现代化研究会 - 新 闻",
      "type": "feed",
      "url": "rsshub://camchina"
    }
  ]
}
```
