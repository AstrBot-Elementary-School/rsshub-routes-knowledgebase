# 泉州师范学院 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `qztc`
- Namespace Name: `泉州师范学院`
- Route Path: `/qztc/jwc/:type`
- Route Name: `教务处`
- Example: `/qztc/jwc/jwdt`
- URL: `www.qztc.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `iQNRen`
- Source Location: `jwc/index.ts`
- Source Module: `_None_`

## Description
| 板块     | 参数 |
| -------- | ---- |
| 教务动态 | jwdt |
| 首 页    | 1020 |
| 岗位介绍 | 1021 |
| 管理文件 | 1022 |
| 教学教改 | 1023 |
| 办事指南 | 1024 |
| 通知公告 | 1025 |
| 下载中心 | 1026 |
| 对外交流 | 1027 |
| 政策文件 | 1028 |
| 会议纪要 | 1029 |

## Parameters
- `type`: 分类，见下表


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
  - `www.qztc.edu.cn/jwc/:type/list.htm`
- `target`: `/jwc/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 板块     | 参数 |\n| -------- | ---- |\n| 教务动态 | jwdt |\n| 首 页    | 1020 |\n| 岗位介绍 | 1021 |\n| 管理文件 | 1022 |\n| 教学教改 | 1023 |\n| 办事指南 | 1024 |\n| 通知公告 | 1025 |\n| 下载中心 | 1026 |\n| 对外交流 | 1027 |\n| 政策文件 | 1028 |\n| 会议纪要 | 1029 |",
  "example": "/qztc/jwc/jwdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc/index.ts",
  "maintainers": [
    "iQNRen"
  ],
  "name": "教务处",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/jwc/:type",
  "radar": [
    {
      "source": [
        "www.qztc.edu.cn/jwc/:type/list.htm"
      ],
      "target": "/jwc/:type"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.qztc.edu.cn"
}
```
