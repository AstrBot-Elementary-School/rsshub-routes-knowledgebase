# 爱奇艺 - 剧集

## Coverage
`index-only`

## Route
- Namespace: `iqiyi`
- Namespace Name: `爱奇艺`
- Route Path: `/iqiyi/album/:id`
- Route Name: `剧集`
- Example: `/iqiyi/album/神武天尊-2020-1b4lufwxd7h`
- URL: `iq.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `album.tsx`
- Source Module: `_None_`

## Description
::: tip
可抓取內容根据服务器所在地区而定
:::

## Parameters
- `id`: 剧集 id, 可在该主页 URL 中找到


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
    "multimedia"
  ],
  "description": "::: tip\n可抓取內容根据服务器所在地区而定\n:::",
  "example": "/iqiyi/album/神武天尊-2020-1b4lufwxd7h",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "album.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "剧集",
  "parameters": {
    "id": "剧集 id, 可在该主页 URL 中找到"
  },
  "path": "/album/:id",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "我自虚空而来，举手诸天崩碎，覆手黄泉寂灭；我为魔、为神、为仙、为人。我是萧晨，也是万物，亦为主宰！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62130677688848384",
      "image": "http://pic6.iqiyipic.com/jisu/20251226/46/e4/f2646da84e162f39b4934ed71a6a4bee_1013_569.webp",
      "ownerUserId": null,
      "siteUrl": "https://www.iq.com/album/the-legend-of-sky-lord-2020-1b4lufwxd7h?lang=en_us",
      "title": "神武天尊",
      "type": "feed",
      "url": "rsshub://iqiyi/album/%E7%A5%9E%E6%AD%A6%E5%A4%A9%E5%B0%8A-2020-1b4lufwxd7h"
    }
  ]
}
```
