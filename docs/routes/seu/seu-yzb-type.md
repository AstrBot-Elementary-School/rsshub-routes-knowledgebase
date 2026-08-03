# 东南大学 - 研究生招生网通知公告

## Coverage
`index-only`

## Route
- Namespace: `seu`
- Namespace Name: `东南大学`
- Route Path: `/seu/yzb/:type`
- Route Name: `研究生招生网通知公告`
- Example: `/seu/yzb/6676`
- URL: `cse.seu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `fuzy112`
- Source Location: `yzb/index.ts`
- Source Module: `_None_`

## Description
| 硕士招生 | 博士招生 | 港澳台及中外合作办学 |
| -------- | -------- | -------------------- |
| 6676     | 6677     | 6679                 |

## Parameters
- `type`: 分类名，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `yzb.seu.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 硕士招生 | 博士招生 | 港澳台及中外合作办学 |\n| -------- | -------- | -------------------- |\n| 6676     | 6677     | 6679                 |",
  "example": "/seu/yzb/6676",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "yzb/index.ts",
  "maintainers": [
    "fuzy112"
  ],
  "name": "研究生招生网通知公告",
  "parameters": {
    "type": "分类名，见下表"
  },
  "path": "/yzb/:type",
  "radar": [
    {
      "source": [
        "yzb.seu.edu.cn/:type/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "东南大学研究生招生网 -- 硕士招生 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "152571187567391744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yzb.seu.edu.cn/6676/list.htm",
      "title": "东南大学研究生招生网 -- 硕士招生",
      "type": "feed",
      "url": "rsshub://seu/yzb/6676"
    },
    {
      "description": "东南大学研究生招生网 -- 博士招生 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "152571487657260032",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yzb.seu.edu.cn/6677/list.htm",
      "title": "东南大学研究生招生网 -- 博士招生",
      "type": "feed",
      "url": "rsshub://seu/yzb/6677"
    }
  ]
}
```
