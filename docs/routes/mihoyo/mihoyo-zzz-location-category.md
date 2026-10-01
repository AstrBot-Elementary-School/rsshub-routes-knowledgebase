# 米哈游 - 绝区零

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/mihoyo/zzz/:location?/:category?`
- Route Name: `绝区零`
- Example: `/mihoyo/zzz`
- URL: `zzz.mihoyo.com/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `Yeye-0426`
- Source Location: `zzz/news.ts`
- Source Module: `_None_`

## Description
#### 新闻 {#mi-ha-you-jue-qu-ling-xin-wen}

| 最新     | 新闻 | 公告   | 活动     |
| -------- | ---- | ------ | -------- |
| news-all | news | notice | activity |

## Parameters
- `location`: 区域，可选 `zh-cn`（国服，简中）或 `zh-tw`（国际服，繁中）
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
  - `zzz.mihoyo.com/news`
- `target`: `/zzz`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "#### 新闻 {#mi-ha-you-jue-qu-ling-xin-wen}\n\n| 最新     | 新闻 | 公告   | 活动     |\n| -------- | ---- | ------ | -------- |\n| news-all | news | notice | activity |",
  "example": "/mihoyo/zzz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "zzz/news.ts",
  "maintainers": [
    "Yeye-0426"
  ],
  "name": "绝区零",
  "parameters": {
    "category": "分类，见下表，默认为最新",
    "location": "区域，可选 `zh-cn`（国服，简中）或 `zh-tw`（国际服，繁中）"
  },
  "path": "/zzz/:location?/:category?",
  "radar": [
    {
      "source": [
        "zzz.mihoyo.com/news"
      ],
      "target": "/zzz"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "最新-绝区零 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "205175880713752576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zzz.mihoyo.com/news?category=273",
      "title": "最新-绝区零",
      "type": "feed",
      "url": "rsshub://mihoyo/zzz/zh-cn"
    },
    {
      "description": "最新-绝区零 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "182164256051058688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zzz.mihoyo.com/news?category=273",
      "title": "最新-绝区零",
      "type": "feed",
      "url": "rsshub://mihoyo/zzz"
    }
  ],
  "url": "zzz.mihoyo.com/news"
}
```
