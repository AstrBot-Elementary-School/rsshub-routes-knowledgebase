# 南京信息工程大学 - NUIST AS（南信大大气科学学院）

## Coverage
`index-only`

## Route
- Namespace: `nuist`
- Namespace Name: `南京信息工程大学`
- Route Path: `/nuist/cas/:category?`
- Route Name: `NUIST AS（南信大大气科学学院）`
- Example: `/nuist/cas/xxgg`
- URL: `bulletin.nuist.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `gylidian`
- Source Location: `cas.ts`
- Source Module: `_None_`

## Description
| 信息公告 | 新闻快讯 | 科学研究 | 网上公示 | 本科教育 | 研究生教育 |
| -------- | -------- | -------- | -------- | -------- | ---------- |
| xxgg     | xwkx     | kxyj     | wsgs     | bkjy     | yjsjy      |

## Parameters
- `category`: 默认为信息公告


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
  "description": "| 信息公告 | 新闻快讯 | 科学研究 | 网上公示 | 本科教育 | 研究生教育 |\n| -------- | -------- | -------- | -------- | -------- | ---------- |\n| xxgg     | xwkx     | kxyj     | wsgs     | bkjy     | yjsjy      |",
  "example": "/nuist/cas/xxgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cas.ts",
  "maintainers": [
    "gylidian"
  ],
  "name": "NUIST AS（南信大大气科学学院）",
  "parameters": {
    "category": "默认为信息公告"
  },
  "path": "/cas/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
