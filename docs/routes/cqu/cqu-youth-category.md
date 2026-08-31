# 重庆大学 - 校团委

## Coverage
`index-only`

## Route
- Namespace: `cqu`
- Namespace Name: `重庆大学`
- Route Path: `/cqu/youth/:category`
- Route Name: `校团委`
- Example: `/cqu/youth/tzdt`
- URL: `cqu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Hagb`
- Source Location: `youth.ts`
- Source Module: `_None_`

## Description
| 通知动态 | 院系风采 | 信息公示 | 文件转载 |
| -------- | -------- | -------- | -------- |
| tzdt     | yxfc     | xxgs     | wjzz     |

## Parameters
- `category`: 分类名


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知动态 | 院系风采 | 信息公示 | 文件转载 |\n| -------- | -------- | -------- | -------- |\n| tzdt     | yxfc     | xxgs     | wjzz     |",
  "example": "/cqu/youth/tzdt",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "youth.ts",
  "maintainers": [
    "Hagb"
  ],
  "name": "校团委",
  "parameters": {
    "category": "分类名"
  },
  "path": "/youth/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
