# 电獭少女 - 精选主题

## Coverage
`index-only`

## Route
- Namespace: `agirls`
- Namespace Name: `电獭少女`
- Route Path: `/agirls/topic/:topic`
- Route Name: `精选主题`
- Example: `/agirls/topic/AppleWatch`
- URL: `agirls.aotter.net`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: 精选主题，可通过下方精选主题列表获得


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
  - `agirls.aotter.net/topic/:topic`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/agirls/topic/AppleWatch",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "topic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "精选主题",
  "parameters": {
    "topic": "精选主题，可通过下方精选主题列表获得"
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "agirls.aotter.net/topic/:topic"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "自助旅行實用攻略集！訂票小技巧、排程App通通教給你。本篇將介紹許多規劃自助旅行的小工具。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131669810084262912",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://agirls.aotter.net/topic/1",
      "title": "自助旅行實用攻略集！- 電獺少女：女孩的科技日常-App、科技酷品、生活與美食",
      "type": "feed",
      "url": "rsshub://agirls/topic/1"
    },
    {
      "description": "Apple Watch 其實不只是一支用來看時間的手錶，還可以用來測試心電圖，成為你健康生活的好夥伴！ - Powered by RSSHub",
      "errorAt": "2025-11-04T01:23:33.865Z",
      "errorMessage": "Failed to fetch\n",
      "id": "125783881831693312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://agirls.aotter.net/topic/AppleWatch",
      "title": "Apple Watch 資訊重點整理- 電獺少女：女孩的科技日常-App、科技酷品、生活與美食",
      "type": "feed",
      "url": "rsshub://agirls/topic/AppleWatch"
    }
  ]
}
```
