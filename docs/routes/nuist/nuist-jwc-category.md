# 南京信息工程大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `nuist`
- Namespace Name: `南京信息工程大学`
- Route Path: `/nuist/jwc/:category?`
- Route Name: `教务处`
- Example: `/nuist/jwc/jxyw`
- URL: `bulletin.nuist.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `gylidian`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 教学要闻 | 学院教学 | 教务管理 | 教学研究 | 教务管理 | 教材建设 | 考试中心 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| jxyw     | xyjx     | jwgl     | jxyj     | sjjx     | jcjs     | kszx     |

## Parameters
- `category`: 默认为教学要闻


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教学要闻 | 学院教学 | 教务管理 | 教学研究 | 教务管理 | 教材建设 | 考试中心 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| jxyw     | xyjx     | jwgl     | jxyj     | sjjx     | jcjs     | kszx     |",
  "example": "/nuist/jwc/jxyw",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "jwc.ts",
  "maintainers": [
    "gylidian"
  ],
  "name": "教务处",
  "parameters": {
    "category": "默认为教学要闻"
  },
  "path": "/jwc/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "南京信息工程大学-教务处：信息通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72519556500486144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.nuist.edu.cn/xxtz/kszx.htm",
      "title": "南京信息工程大学-教务处：信息通知",
      "type": "feed",
      "url": "rsshub://nuist/jwc/kszx"
    },
    {
      "description": "南京信息工程大学-教务处：信息通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72519284425781248",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.nuist.edu.cn/xxtz/jwgl.htm",
      "title": "南京信息工程大学-教务处：信息通知",
      "type": "feed",
      "url": "rsshub://nuist/jwc/jwgl"
    }
  ]
}
```
