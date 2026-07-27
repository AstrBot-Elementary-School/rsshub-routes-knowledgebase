# Konachan.com Anime Wallpapers - Popular Recent Posts

## Coverage
`index-only`

## Route
- Namespace: `konachan`
- Namespace Name: `Konachan.com Anime Wallpapers`
- Route Path: `/konachan/post/popular_recent/:period?`
- Route Name: `Popular Recent Posts`
- Example: `/konachan/post/popular_recent/1d`
- URL: `konachan.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `magic-akari, NekoAria, sineeeee`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
| 最近 24 小时 | 最近一周 | 最近一月 | 最近一年 |
| ------------ | -------- | -------- | -------- |
| 1d           | 1w       | 1m       | 1y       |

## Parameters
- `period`: {"default": "1d", "description": "展示时间", "options": [{"label": "最近 24 小时", "value": "1d"}, {"label": "最近一周", "value": "1w"}, {"label": "最近一月", "value": "1m"}, {"label": "最近一年", "value": "1y"}]}
- `safe_search`: {"default": "false", "description": "是否使用无r18的站点konachan.net，若是,则在路径前加上 `/sfw`，如`/konachan/sfw/post/popular_recent/1d`，若否则默认使用 konachan.com"}


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `konachan.com/post`
### Rule 2
- `source`:
  - `konachan.net/post`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "| 最近 24 小时 | 最近一周 | 最近一月 | 最近一年 |\n| ------------ | -------- | -------- | -------- |\n| 1d           | 1w       | 1m       | 1y       |",
  "example": "/konachan/post/popular_recent/1d",
  "features": {
    "nsfw": true
  },
  "heat": 1184,
  "location": "post.ts",
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
    },
    "safe_search": {
      "default": "false",
      "description": "是否使用无r18的站点konachan.net，若是,则在路径前加上 `/sfw`，如`/konachan/sfw/post/popular_recent/1d`，若否则默认使用 konachan.com"
    }
  },
  "path": [
    "/post/popular_recent/:period?",
    "/sfw/post/popular_recent/:period?"
  ],
  "radar": [
    {
      "source": [
        "konachan.com/post"
      ]
    },
    {
      "source": [
        "konachan.net/post"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Last 24 hours - konachan.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62201931989535744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://konachan.com/post/popular_recent?period=1d",
      "title": "Last 24 hours - konachan.com",
      "type": "feed",
      "url": "rsshub://konachan/post/popular_recent/1d"
    },
    {
      "description": "Last week - konachan.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62202498728230912",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://konachan.com/post/popular_recent?period=1w",
      "title": "Last week - konachan.com",
      "type": "feed",
      "url": "rsshub://konachan/post/popular_recent/1w"
    }
  ],
  "view": 2
}
```
