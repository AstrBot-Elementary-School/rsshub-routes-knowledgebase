# 豆瓣 - 频道专题

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/channel/:id/:nav?`
- Route Name: `频道专题`
- Example: `/douban/channel/30168934/hot`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `umm233`
- Source Location: `channel/topic.ts`
- Source Module: `_None_`

## Description
| 默认    | 热门 | 最新 |
| ------- | ---- | ---- |
| default | hot  | new  |

## Parameters
- `id`: 频道id
- `nav`: 专题分类，可选，默认为 default


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
    "social-media"
  ],
  "description": "| 默认    | 热门 | 最新 |\n| ------- | ---- | ---- |\n| default | hot  | new  |",
  "example": "/douban/channel/30168934/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "channel/topic.ts",
  "maintainers": [
    "umm233"
  ],
  "name": "频道专题",
  "parameters": {
    "id": "频道id",
    "nav": "专题分类，可选，默认为 default"
  },
  "path": "/channel/:id/:nav?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 316063653853 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
