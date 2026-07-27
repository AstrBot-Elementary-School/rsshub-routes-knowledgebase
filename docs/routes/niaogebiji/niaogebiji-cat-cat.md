# 鸟哥笔记 - 分类目录

## Coverage
`index-only`

## Route
- Namespace: `niaogebiji`
- Namespace Name: `鸟哥笔记`
- Route Path: `/niaogebiji/cat/:cat`
- Route Name: `分类目录`
- Example: `/niaogebiji/cat/103`
- URL: `niaogebiji.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `cKotoriKat`
- Source Location: `cat.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `cat`: 如 https://www.niaogebiji.com/cat/103，最后的数字就是id


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
  - `niaogebiji.com/cat/:cat`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/niaogebiji/cat/103",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 103,
  "location": "cat.ts",
  "maintainers": [
    "cKotoriKat"
  ],
  "name": "分类目录",
  "parameters": {
    "cat": "如 https://www.niaogebiji.com/cat/103，最后的数字就是id"
  },
  "path": "/cat/:cat",
  "radar": [
    {
      "source": [
        "niaogebiji.com/cat/:cat"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "私域社群聚合私域流量、私域运营、私域营销、社群运营、社群管理干货知识，一站式解决私域社群运营管理问题。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78297780823985152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.niaogebiji.com/cat/101",
      "title": "私域流量_社群运营-鸟哥笔记",
      "type": "feed",
      "url": "rsshub://niaogebiji/cat/101"
    },
    {
      "description": "内容运营聚合内容运营知识、内容运营能力、内容运营主要工作等干货知识，一站式解决内容运营管理、内容运营主要工作问题。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71110389108097024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.niaogebiji.com/cat/136",
      "title": "内容运营_内容运营知识-鸟哥笔记",
      "type": "feed",
      "url": "rsshub://niaogebiji/cat/136"
    }
  ],
  "url": "niaogebiji.com/"
}
```
