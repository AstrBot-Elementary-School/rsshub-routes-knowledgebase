# 中南大学 - 校长信箱

## Coverage
`index-only`

## Route
- Namespace: `csu`
- Namespace Name: `中南大学`
- Route Path: `/csu/mail/:type?`
- Route Name: `校长信箱`
- Example: `/csu/mail`
- URL: `career.csu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `j1g5awi`
- Source Location: `mail.ts`
- Source Module: `_None_`

## Description
| 类型 | 校长信箱 | 党委信箱 |
| ---- | -------- | -------- |
| 参数 | 01       | 02       |

## Parameters
- `type`: 类型


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
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
  "description": "| 类型 | 校长信箱 | 党委信箱 |\n| ---- | -------- | -------- |\n| 参数 | 01       | 02       |",
  "example": "/csu/mail",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "mail.ts",
  "maintainers": [
    "j1g5awi"
  ],
  "name": "校长信箱",
  "parameters": {
    "type": "类型"
  },
  "path": "/mail/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processImmediate (node:internal/timers:472:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中南大学学校信箱 - 校长信箱 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81350858120764416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://oa.csu.edu.cn/mailbox/NoAuth/MailList_Pub?tp=01",
      "title": "中南大学学校信箱 - 校长信箱",
      "type": "feed",
      "url": "rsshub://csu/mail"
    }
  ]
}
```
