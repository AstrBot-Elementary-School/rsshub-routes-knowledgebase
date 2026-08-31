# 西北农林科技大学 - 校园要闻

## Coverage
`index-only`

## Route
- Namespace: `nwafu`
- Namespace Name: `西北农林科技大学`
- Route Path: `/nwafu/:type?`
- Route Name: `校园要闻`
- Example: `/nwafu/lib`
- URL: `nwafu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `karinido`
- Source Location: `all.ts`
- Source Module: `_None_`

## Description
通知类别

| 图书馆 | 共青团团委 | 信工学院 | 后勤管理处 | 计划财务处 | 教务处 | 新闻网 | 信息化管理处 | 研究生院 | 农业科学院 | 机械与电子工程学院 | 学术活动 | 生命科学学院 |
| ------ | ---------- | -------- | ---------- | ---------- | ------ | ------ | ------------ | -------- | ---------- | ------------------ | -------- | ------------ |
| lib    | youth      | cie      | gs         | jcc        | jiaowu | news   | nic          | yjshy    | nxy        | cmee               | xshd     | sm           |

## Parameters
- `type`: 默认为 `jiaowu`


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
  "description": "通知类别\n\n| 图书馆 | 共青团团委 | 信工学院 | 后勤管理处 | 计划财务处 | 教务处 | 新闻网 | 信息化管理处 | 研究生院 | 农业科学院 | 机械与电子工程学院 | 学术活动 | 生命科学学院 |\n| ------ | ---------- | -------- | ---------- | ---------- | ------ | ------ | ------------ | -------- | ---------- | ------------------ | -------- | ------------ |\n| lib    | youth      | cie      | gs         | jcc        | jiaowu | news   | nic          | yjshy    | nxy        | cmee               | xshd     | sm           |",
  "example": "/nwafu/lib",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "all.ts",
  "maintainers": [
    "karinido"
  ],
  "name": "校园要闻",
  "parameters": {
    "type": "默认为 `jiaowu`"
  },
  "path": "/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
