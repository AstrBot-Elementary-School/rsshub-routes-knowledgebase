# 量子位 - 标签

## Coverage
`index-only`

## Route
- Namespace: `qbitai`
- Namespace Name: `量子位`
- Route Path: `/qbitai/tag/:tag`
- Route Name: `标签`
- Example: `/qbitai/tag/大语言模型`
- URL: `qbitai.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `FuryMartin`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: 标签名


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
  - `qbitai.com/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/qbitai/tag/大语言模型",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 79,
  "location": "tag.ts",
  "maintainers": [
    "FuryMartin"
  ],
  "name": "标签",
  "parameters": {
    "tag": "标签名"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "qbitai.com/tag/:tag"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "量子位-大语言模型 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52357479513292816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qbitai.com/tag/%E5%A4%A7%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B",
      "title": "量子位-大语言模型",
      "type": "feed",
      "url": "rsshub://qbitai/tag/%E5%A4%A7%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B"
    },
    {
      "description": "量子位-具身智能 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82271529316734976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qbitai.com/tag/%E5%85%B7%E8%BA%AB%E6%99%BA%E8%83%BD",
      "title": "量子位-具身智能",
      "type": "feed",
      "url": "rsshub://qbitai/tag/%E5%85%B7%E8%BA%AB%E6%99%BA%E8%83%BD"
    }
  ]
}
```
