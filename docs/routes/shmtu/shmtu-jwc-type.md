# 上海海事大学 - 教务信息

## Coverage
`index-only`

## Route
- Namespace: `shmtu`
- Namespace Name: `上海海事大学`
- Route Path: `/shmtu/jwc/:type`
- Route Name: `教务信息`
- Example: `/shmtu/jwc/jwgg`
- URL: `jwc.shmtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `imbytecat, simonsmh`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 教务公告 | 教务新闻 |
| -------- | -------- |
| jwgg     | jwxw     |

## Parameters
- `type`: 类型名称


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
  - `jwc.shmtu.edu.cn/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教务公告 | 教务新闻 |\n| -------- | -------- |\n| jwgg     | jwxw     |",
  "example": "/shmtu/jwc/jwgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "jwc.ts",
  "maintainers": [
    "imbytecat",
    "simonsmh"
  ],
  "name": "教务信息",
  "parameters": {
    "type": "类型名称"
  },
  "path": "/jwc/:type",
  "radar": [
    {
      "source": [
        "jwc.shmtu.edu.cn/:type"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "上海海事大学 教务信息 - Powered by RSSHub",
      "errorAt": "2025-12-31T14:21:21.415Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "181348894722030592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.shmtu.edu.cn/jwgg",
      "title": "上海海事大学 教务公告",
      "type": "feed",
      "url": "rsshub://shmtu/jwc/jwgg"
    }
  ]
}
```
