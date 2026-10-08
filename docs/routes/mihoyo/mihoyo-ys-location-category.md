# 米哈游 - 原神

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/mihoyo/ys/:location?/:category?`
- Route Name: `原神`
- Example: `/mihoyo/ys`
- URL: `genshin.hoyoverse.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `ys/news.ts`
- Source Module: `_None_`

## Description
#### 新闻 {#mi-ha-you-yuan-shen-xin-wen}

| 最新   | 新闻 | 公告   | 活动     |
| ------ | ---- | ------ | -------- |
| latest | news | notice | activity |

## Parameters
- `location`: 区域，可选 `main`（简中）或 `zh-tw`（繁中）
- `category`: 分类，见下表，默认为最新


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
  - `genshin.hoyoverse.com/:location/news`
- `target`: `/ys/:location`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "#### 新闻 {#mi-ha-you-yuan-shen-xin-wen}\n\n| 最新   | 新闻 | 公告   | 活动     |\n| ------ | ---- | ------ | -------- |\n| latest | news | notice | activity |",
  "example": "/mihoyo/ys",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 58,
  "location": "ys/news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "原神",
  "parameters": {
    "category": "分类，见下表，默认为最新",
    "location": "区域，可选 `main`（简中）或 `zh-tw`（繁中）"
  },
  "path": "/ys/:location?/:category?",
  "radar": [
    {
      "source": [
        "genshin.hoyoverse.com/:location/news"
      ],
      "target": "/ys/:location"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:101:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "原神 - 最新 - Powered by RSSHub",
      "errorAt": "2026-10-06T21:40:43.948Z",
      "errorMessage": "[GET] \"https://api-takumi-static.mihoyo.com/content_v2_user/app/16471662a82d418a/getContentList?iPage=1&sLangKey=zh-cn&iChanId=719&iPageSize=50\": 522 <none>\n",
      "id": "156266162055355392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ys.mihoyo.com/main/news/719",
      "title": "原神 - 最新",
      "type": "feed",
      "url": "rsshub://mihoyo/ys/main"
    },
    {
      "description": "原神 - 最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68834268354564096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ys.mihoyo.com/main/news/719",
      "title": "原神 - 最新",
      "type": "feed",
      "url": "rsshub://mihoyo/ys"
    }
  ]
}
```
