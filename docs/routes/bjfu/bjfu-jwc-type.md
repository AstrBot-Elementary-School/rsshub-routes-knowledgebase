# 北京林业大学 - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `bjfu`
- Namespace Name: `北京林业大学`
- Route Path: `/bjfu/jwc/:type`
- Route Name: `教务处通知公告`
- Example: `/bjfu/jwc/jwkx`
- URL: `graduate.bjfu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `markmingjie`
- Source Location: `jwc/index.ts`
- Source Module: `_None_`

## Description
| 教务快讯 | 考试信息 | 课程信息 | 教改动态 | 图片新闻 |
| -------- | -------- | -------- | -------- | -------- |
| jwkx     | ksxx     | kcxx     | jgdt     | tpxw     |

## Parameters
- `type`: 通知类别


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
  - `jwc.bjfu.edu.cn/:type/index.html`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教务快讯 | 考试信息 | 课程信息 | 教改动态 | 图片新闻 |\n| -------- | -------- | -------- | -------- | -------- |\n| jwkx     | ksxx     | kcxx     | jgdt     | tpxw     |",
  "example": "/bjfu/jwc/jwkx",
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
    "markmingjie"
  ],
  "name": "教务处通知公告",
  "parameters": {
    "type": "通知类别"
  },
  "path": "/jwc/:type",
  "radar": [
    {
      "source": [
        "jwc.bjfu.edu.cn/:type/index.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processTimers (node:internal/timers:538:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
