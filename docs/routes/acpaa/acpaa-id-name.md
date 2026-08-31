# 中华全国专利代理师协会 - 标签

## Coverage
`index-only`

## Route
- Namespace: `acpaa`
- Namespace Name: `中华全国专利代理师协会`
- Route Path: `/acpaa/:id?/:name?`
- Route Name: `标签`
- Example: `/acpaa`
- URL: `acpaa.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 标签 id，默认为 1，可在对应标签页 URL 中找到
- `name`: 标签名称，默认为重要通知，可在对应标签页 URL 中找到


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
  "example": "/acpaa",
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
  "name": "标签",
  "parameters": {
    "id": "标签 id，默认为 1，可在对应标签页 URL 中找到",
    "name": "标签名称，默认为重要通知，可在对应标签页 URL 中找到"
  },
  "path": "/:id?/:name?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
