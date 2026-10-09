# 前瞻网 - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `qianzhan`
- Namespace Name: `前瞻网`
- Route Path: `/qianzhan/analyst/rank/:type?`
- Route Name: `排行榜`
- Example: `/qianzhan/analyst/rank/week`
- URL: `qianzhan.com/analyst`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `moke8`
- Source Location: `rank.ts`
- Source Module: `_None_`

## Description
| 周排行 | 月排行 |
| ------ | ------ |
| week   | month  |

## Parameters
- `type`: 分类，见下表


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
  - `qianzhan.com/analyst`
  - `qianzhan.com/`
- `target`: `/analyst/rank`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 周排行 | 月排行 |\n| ------ | ------ |\n| week   | month  |",
  "example": "/qianzhan/analyst/rank/week",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 109,
  "location": "rank.ts",
  "maintainers": [
    "moke8"
  ],
  "name": "排行榜",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/analyst/rank/:type?",
  "radar": [
    {
      "source": [
        "qianzhan.com/analyst",
        "qianzhan.com/"
      ],
      "target": "/analyst/rank"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "前瞻经济学人 - 月排行 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76424376514969600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qianzhan.com/analyst/",
      "title": "前瞻经济学人 - 月排行",
      "type": "feed",
      "url": "rsshub://qianzhan/analyst/rank"
    },
    {
      "description": "前瞻经济学人 - 周排行 - Powered by RSSHub",
      "errorAt": "2026-09-30T02:16:15.225Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n[GET] \"https://www.qianzhan.com/analyst/\": 500 Internal Server Error\n",
      "id": "65666355458866176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qianzhan.com/analyst/",
      "title": "前瞻经济学人 - 周排行",
      "type": "feed",
      "url": "rsshub://qianzhan/analyst/rank/week"
    }
  ],
  "url": "qianzhan.com/analyst"
}
```
