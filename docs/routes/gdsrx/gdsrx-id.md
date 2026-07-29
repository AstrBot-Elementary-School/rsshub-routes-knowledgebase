# 广东省食品药品审评认证技术协会 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `gdsrx`
- Namespace Name: `广东省食品药品审评认证技术协会`
- Route Path: `/gdsrx/:id?`
- Route Name: `栏目`
- Example: `/gdsrx`
- URL: `gdsrx.org.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 栏目名称          | 栏目 id |
| ----------------- | ------- |
| 法规文库          | 10      |
| 法规资讯          | 12      |
| 专家供稿          | 13      |
| 协会动态 会员动态 | 20      |
| 协会动态          | 37      |
| 协会通知公告      | 38      |
| 会员动态          | 39      |

## Parameters
- `id`: 栏目 id，可在对应栏目页 URL 中找到，见下表，默认为法规文库


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
  "description": "| 栏目名称          | 栏目 id |\n| ----------------- | ------- |\n| 法规文库          | 10      |\n| 法规资讯          | 12      |\n| 专家供稿          | 13      |\n| 协会动态 会员动态 | 20      |\n| 协会动态          | 37      |\n| 协会通知公告      | 38      |\n| 会员动态          | 39      |",
  "example": "/gdsrx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "id": "栏目 id，可在对应栏目页 URL 中找到，见下表，默认为法规文库"
  },
  "path": "/:id?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
