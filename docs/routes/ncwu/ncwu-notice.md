# 华北水利水电大学 - 学校通知

## Coverage
`index-only`

## Route
- Namespace: `ncwu`
- Namespace Name: `华北水利水电大学`
- Route Path: `/ncwu/notice`
- Route Name: `学校通知`
- Example: `/ncwu/notice`
- URL: `ncwu.edu.cn/xxtz.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `vuhe`
- Source Location: `notice.ts`
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
  - `ncwu.edu.cn/xxtz.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ncwu/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "notice.ts",
  "maintainers": [
    "vuhe"
  ],
  "name": "学校通知",
  "parameters": {},
  "path": "/notice",
  "radar": [
    {
      "source": [
        "ncwu.edu.cn/xxtz.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "学校通知-欢迎访问华北水利水电大学 - Powered by RSSHub",
      "errorAt": "2026-04-23T08:21:32.238Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "203856512518861824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ncwu.edu.cn/xxtz.htm",
      "title": "学校通知-欢迎访问华北水利水电大学",
      "type": "feed",
      "url": "rsshub://ncwu/notice"
    }
  ],
  "url": "ncwu.edu.cn/xxtz.htm"
}
```
