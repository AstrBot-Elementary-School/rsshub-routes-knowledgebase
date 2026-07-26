# 华南理工大学 - 机械与汽车工程学院 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `scut`
- Namespace Name: `华南理工大学`
- Route Path: `/scut/smae/:category?`
- Route Name: `机械与汽车工程学院 - 通知公告`
- Example: `/scut/smae/yjsjw`
- URL: `jw.scut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Ermaotie`
- Source Location: `smae/notice.ts`
- Source Module: `_None_`

## Description
| 公务信息 | 党建工作 | 人事工作 | 学生工作 | 科研实验室 | 本科生教务 | 研究生教务 |
| -------- | -------- | -------- | -------- | ---------- | ---------- | ---------- |
| gwxx     | djgz     | rsgz     | xsgz     | kysys      | bksjw      | yjsjw      |

## Parameters
- `category`: 通知分类，默认为 `yjsjw`


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
  "description": "| 公务信息 | 党建工作 | 人事工作 | 学生工作 | 科研实验室 | 本科生教务 | 研究生教务 |\n| -------- | -------- | -------- | -------- | ---------- | ---------- | ---------- |\n| gwxx     | djgz     | rsgz     | xsgz     | kysys      | bksjw      | yjsjw      |",
  "example": "/scut/smae/yjsjw",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "smae/notice.ts",
  "maintainers": [
    "Ermaotie"
  ],
  "name": "机械与汽车工程学院 - 通知公告",
  "parameters": {
    "category": "通知分类，默认为 `yjsjw`"
  },
  "path": "/smae/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "华南理工大学机械与汽车工程学院 - 本科生教务 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "161299824606114816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www2.scut.edu.cn/smae/20619/list.htm",
      "title": "华南理工大学机械与汽车工程学院 - 本科生教务",
      "type": "feed",
      "url": "rsshub://scut/smae/bksjw"
    }
  ]
}
```
