# 南京大学 - 人才招聘网

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/rczp/:type`
- Route Name: `人才招聘网`
- Example: `/nju/rczp/xxfb`
- URL: `admission.nju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `rczp.ts`
- Source Module: `_None_`

## Description
| 信息发布 | 教研类岗位 | 管理岗位及其他 |
| -------- | ---------- | -------------- |
| xxfb     | jylgw      | gllgw          |

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
  - `rczp.nju.edu.cn/sylm/:type/index.html`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 信息发布 | 教研类岗位 | 管理岗位及其他 |\n| -------- | ---------- | -------------- |\n| xxfb     | jylgw      | gllgw          |",
  "example": "/nju/rczp/xxfb",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "rczp.ts",
  "maintainers": [
    "ret-1"
  ],
  "name": "人才招聘网",
  "parameters": {
    "type": "分类名"
  },
  "path": "/rczp/:type",
  "radar": [
    {
      "source": [
        "rczp.nju.edu.cn/sylm/:type/index.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "人才招聘-信息发布 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62660840174386176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://rczp.nju.edu.cn/sylm/xxfb/index.html",
      "title": "人才招聘-信息发布",
      "type": "feed",
      "url": "rsshub://nju/rczp/xxfb"
    }
  ]
}
```
