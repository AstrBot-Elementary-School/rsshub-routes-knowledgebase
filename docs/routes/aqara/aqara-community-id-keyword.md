# Aqara - 社区

## Coverage
`index-only`

## Route
- Namespace: `aqara`
- Namespace Name: `Aqara`
- Route Path: `/aqara/community/:id?/:keyword?`
- Route Name: `社区`
- Example: `/aqara/community`
- URL: `aqara.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `community.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 分类 id，可在对应分类页 URL 中找到，默认为全部
- `keyword`: 关键字，默认为空


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
    "other"
  ],
  "example": "/aqara/community",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "community.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "社区",
  "parameters": {
    "id": "分类 id，可在对应分类页 URL 中找到，默认为全部",
    "keyword": "关键字，默认为空"
  },
  "path": "/community/:id?/:keyword?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
