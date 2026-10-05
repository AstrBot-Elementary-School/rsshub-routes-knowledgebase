# 湖南人事考试网 - 公告

## Coverage
`index-only`

## Route
- Namespace: `hunanpea`
- Namespace Name: `湖南人事考试网`
- Route Path: `/hunanpea/rsks/:guid`
- Route Name: `公告`
- Example: `/hunanpea/rsks/2f1a6239-b4dc-491b-92af-7d95e0f0543e`
- URL: `rsks.hunanpea.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `TonyRL`
- Source Location: `rsks.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `guid`: 分类 id，可在 URL 中找到


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
  - `rsks.hunanpea.com/Category/:guid/ArticlesByCategory.do`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/hunanpea/rsks/2f1a6239-b4dc-491b-92af-7d95e0f0543e",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "rsks.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "公告",
  "parameters": {
    "guid": "分类 id，可在 URL 中找到"
  },
  "path": "/rsks/:guid",
  "radar": [
    {
      "source": [
        "rsks.hunanpea.com/Category/:guid/ArticlesByCategory.do"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:101:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "公务员及事业单位考试 - 湖南人事考试网 - Powered by RSSHub",
      "errorAt": "2026-07-31T11:39:58.051Z",
      "errorMessage": "Failed to fetch\n",
      "id": "62787884154546176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://rsks.hunanpea.com/Category/c5a6f516-fd54-4578-90bd-0cb6a1c95570/ArticlesByCategory.do?PageIndex=1",
      "title": "公务员及事业单位考试 - 湖南人事考试网",
      "type": "feed",
      "url": "rsshub://hunanpea/rsks/c5a6f516-fd54-4578-90bd-0cb6a1c95570"
    },
    {
      "description": "新闻公告 - 湖南人事考试网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65998206582691840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://rsks.hunanpea.com/Category/2f1a6239-b4dc-491b-92af-7d95e0f0543e/ArticlesByCategory.do?PageIndex=1",
      "title": "新闻公告 - 湖南人事考试网",
      "type": "feed",
      "url": "rsshub://hunanpea/rsks/2f1a6239-b4dc-491b-92af-7d95e0f0543e"
    }
  ]
}
```
