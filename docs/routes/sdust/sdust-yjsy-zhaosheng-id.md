# 山东科技大学 - 研究生招生网

## Coverage
`index-only`

## Route
- Namespace: `sdust`
- Namespace Name: `山东科技大学`
- Route Path: `/sdust/yjsy/zhaosheng/:id?`
- Route Name: `研究生招生网`
- Example: `/sdust/yjsy/zhaosheng`
- URL: `sdust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `yjsy/zhaosheng.ts`
- Source Module: `_None_`

## Description
栏目

| 招生简章 | 专业目录 | 往届录取 | 管理规定 | 资料下载 |
| -------- | -------- | -------- | -------- | -------- |
| zsjz     | zyml     | wjlq     | glgd     | zlxz     |

| 通知公告 | 博士招生 | 硕士招生 | 推免生招生 | 招生宣传 |
| -------- | -------- | -------- | ---------- | -------- |
| tzgg     | bszs     | sszs     | tms        | zsxc     |

## Parameters
- `id`: 栏目 id，见下表，默认为通知公告


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
  "description": "栏目\n\n| 招生简章 | 专业目录 | 往届录取 | 管理规定 | 资料下载 |\n| -------- | -------- | -------- | -------- | -------- |\n| zsjz     | zyml     | wjlq     | glgd     | zlxz     |\n\n| 通知公告 | 博士招生 | 硕士招生 | 推免生招生 | 招生宣传 |\n| -------- | -------- | -------- | ---------- | -------- |\n| tzgg     | bszs     | sszs     | tms        | zsxc     |",
  "example": "/sdust/yjsy/zhaosheng",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "yjsy/zhaosheng.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "研究生招生网",
  "parameters": {
    "id": "栏目 id，见下表，默认为通知公告"
  },
  "path": "/yjsy/zhaosheng/:id?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
