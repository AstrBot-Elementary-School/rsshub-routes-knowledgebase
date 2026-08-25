# 东南大学 - 网络空间安全学院 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `seu`
- Namespace Name: `东南大学`
- Route Path: `/seu/cyber/tzgg`
- Route Name: `网络空间安全学院 - 通知公告`
- Example: `/seu/cyber/tzgg`
- URL: `cse.seu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `shrugginG`
- Source Location: `cyber/index.ts`
- Source Module: `_None_`

## Description
东南大学网络空间安全学院通知公告

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
  - `cyber.seu.edu.cn/tzgg/list.htm`
  - `cyber.seu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "东南大学网络空间安全学院通知公告",
  "example": "/seu/cyber/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "cyber/index.ts",
  "maintainers": [
    "shrugginG"
  ],
  "name": "网络空间安全学院 - 通知公告",
  "parameters": {},
  "path": "/cyber/tzgg",
  "radar": [
    {
      "source": [
        "cyber.seu.edu.cn/tzgg/list.htm",
        "cyber.seu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "东南大学网络空间安全学院通知公告RSS - Powered by RSSHub",
      "errorAt": "2026-03-13T23:29:29.463Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "162717375260193792",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cyber.seu.edu.cn/tzgg/list.htm",
      "title": "东南大学网络空间安全学院 - 通知公告",
      "type": "feed",
      "url": "rsshub://seu/cyber/tzgg"
    }
  ]
}
```
