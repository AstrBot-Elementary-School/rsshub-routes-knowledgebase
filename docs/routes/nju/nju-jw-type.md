# 南京大学 - 本科生院

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/jw/:type`
- Route Name: `本科生院`
- Example: `/nju/jw/ggtz`
- URL: `admission.nju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cqjjjzr`
- Source Location: `jw.ts`
- Source Module: `_None_`

## Description
| 公告通知 | 教学动态 |
| -------- | -------- |
| ggtz     | jxdt     |

## Parameters
- `type`: 分类名


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
  - `jw.nju.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 公告通知 | 教学动态 |\n| -------- | -------- |\n| ggtz     | jxdt     |",
  "example": "/nju/jw/ggtz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "jw.ts",
  "maintainers": [
    "cqjjjzr"
  ],
  "name": "本科生院",
  "parameters": {
    "type": "分类名"
  },
  "path": "/jw/:type",
  "radar": [
    {
      "source": [
        "jw.nju.edu.cn/:type/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "本科生院-公告通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62659747935681536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jw.nju.edu.cn/ggtz/list.htm",
      "title": "本科生院-公告通知",
      "type": "feed",
      "url": "rsshub://nju/jw/ggtz"
    },
    {
      "description": "本科生院-教学动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "163579923082247168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jw.nju.edu.cn/_s414/24774/list.psp",
      "title": "本科生院-教学动态",
      "type": "feed",
      "url": "rsshub://nju/jw/jxdt"
    }
  ]
}
```
