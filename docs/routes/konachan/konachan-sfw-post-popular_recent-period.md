# Konachan.com Anime Wallpapers - Popular Recent Posts

## Coverage
`index-only`

## Route
- Namespace: `konachan`
- Namespace Name: `Konachan.com Anime Wallpapers`
- Route Path: `/konachan/sfw/post/popular_recent/:period?`
- Route Name: `Popular Recent Posts`
- Example: `/konachan/sfw/post/popular_recent/1d`
- URL: `konachan.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `magic-akari, NekoAria, sineeeee`
- Source Location: `sfw-post.ts`
- Source Module: `_None_`

## Description
| 最近 24 小时 | 最近一周 | 最近一月 | 最近一年 |
| ------------ | -------- | -------- | -------- |
| 1d           | 1w       | 1m       | 1y       |

## Parameters
- `period`: {"default": "1d", "description": "展示时间", "options": [{"label": "最近 24 小时", "value": "1d"}, {"label": "最近一周", "value": "1w"}, {"label": "最近一月", "value": "1m"}, {"label": "最近一年", "value": "1y"}]}


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `konachan.net/post`
- `target`: `/sfw/post/popular_recent`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "| 最近 24 小时 | 最近一周 | 最近一月 | 最近一年 |\n| ------------ | -------- | -------- | -------- |\n| 1d           | 1w       | 1m       | 1y       |",
  "example": "/konachan/sfw/post/popular_recent/1d",
  "features": {
    "nsfw": true
  },
  "heat": 18,
  "location": "sfw-post.ts",
  "maintainers": [
    "magic-akari",
    "NekoAria",
    "sineeeee"
  ],
  "name": "Popular Recent Posts",
  "parameters": {
    "period": {
      "default": "1d",
      "description": "展示时间",
      "options": [
        {
          "label": "最近 24 小时",
          "value": "1d"
        },
        {
          "label": "最近一周",
          "value": "1w"
        },
        {
          "label": "最近一月",
          "value": "1m"
        },
        {
          "label": "最近一年",
          "value": "1y"
        }
      ]
    }
  },
  "path": "/sfw/post/popular_recent/:period?",
  "radar": [
    {
      "source": [
        "konachan.net/post"
      ],
      "target": "/sfw/post/popular_recent"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Last week - konachan.net - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155092597000609792",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://konachan.net/post/popular_recent?period=1w",
      "title": "Last week - konachan.net",
      "type": "feed",
      "url": "rsshub://konachan/sfw/post/popular_recent/1w"
    },
    {
      "description": "Last 24 hours - konachan.net - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155092706851868672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://konachan.net/post/popular_recent?period=1d",
      "title": "Last 24 hours - konachan.net",
      "type": "feed",
      "url": "rsshub://konachan/sfw/post/popular_recent/1d"
    }
  ],
  "view": 2
}
```
