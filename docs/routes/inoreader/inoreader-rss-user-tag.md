# Inoreader - RSS

## Coverage
`index-only`

## Route
- Namespace: `inoreader`
- Namespace Name: `Inoreader`
- Route Path: `/inoreader/rss/:user/:tag`
- Route Name: `RSS`
- Example: `/inoreader/rss/1005137674/user-favorites`
- URL: `inoreader.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `IvanWng97`
- Source Location: `rss.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: user id, the interger after user/ in the example URL
- `tag`: tag, the string after tag/ in the example URL


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
    "reading"
  ],
  "example": "/inoreader/rss/1005137674/user-favorites",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "rss.ts",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "RSS",
  "parameters": {
    "tag": "tag, the string after tag/ in the example URL",
    "user": "user id, the interger after user/ in the example URL"
  },
  "path": "/rss/:user/:tag",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Yifan's favorite articles on Inoreader - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60319382185805824",
      "image": "https://www.inoreader.com/brand/img/ino_app_icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.inoreader.com/stream/user/1005137674/tag/user-favorites/view/html",
      "title": "Yifan's favorite articles on Inoreader",
      "type": "feed",
      "url": "rsshub://inoreader/rss/1005137674/user-favorites"
    }
  ],
  "view": 0
}
```
