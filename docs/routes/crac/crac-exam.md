# 中国无线电协会业余无线电分会 - 考试信息

## Coverage
`index-only`

## Route
- Namespace: `crac`
- Namespace Name: `中国无线电协会业余无线电分会`
- Route Path: `/crac/exam`
- Route Name: `考试信息`
- Example: `/crac/exam`
- URL: `www.crac.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `admxj`
- Source Location: `exam.tsx`
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
  - `www.crac.org.cn/*`
- `target`: `/exam`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/crac/exam",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "exam.tsx",
  "maintainers": [
    "admxj"
  ],
  "name": "考试信息",
  "path": "/exam",
  "radar": [
    {
      "source": [
        "www.crac.org.cn/*"
      ],
      "target": "/exam"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:101:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "考试信息-中国无线电协会业余无线电分会 - Powered by RSSHub",
      "errorAt": "2026-02-14T01:57:22.686Z",
      "errorMessage": "[POST] \"http://82.157.138.16:8091/CRAC/app/exam_advice/examAdviceList\": 403 Forbidden\n",
      "id": "138468429736494080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://82.157.138.16:8091/CRAC/crac/pages/list_examMsg.html",
      "title": "考试信息-中国无线电协会业余无线电分会",
      "type": "feed",
      "url": "rsshub://crac/exam"
    }
  ]
}
```
