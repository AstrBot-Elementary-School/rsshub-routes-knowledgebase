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
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "考试信息-中国无线电协会业余无线电分会 - Powered by RSSHub",
      "errorAt": "2026-02-14T01:57:22.686Z",
      "errorMessage": "[POST] \"http://82.157.138.16:8091/CRAC/app/exam_advice/examAdviceList\": <no response> fetch failed (Connect Timeout Error (attempted address: 82.157.138.16:8091, timeout: 10000ms))\n",
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
