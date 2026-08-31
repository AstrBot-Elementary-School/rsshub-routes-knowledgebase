# 第一会所 - 作者

## Coverage
`index-only`

## Route
- Namespace: `sis001`
- Namespace Name: `第一会所`
- Route Path: `/sis001/author/:id?`
- Route Name: `作者`
- Example: `/sis001/author/13131575`
- URL: `sis001.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `keocheung`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 作者 ID，可以在作者的个人空间地址找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/sis001/author/13131575",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 32,
  "location": "author.ts",
  "maintainers": [
    "keocheung"
  ],
  "name": "作者",
  "parameters": {
    "id": "作者 ID，可以在作者的个人空间地址找到"
  },
  "path": "/author/:id?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "weiweix120的主题 - Powered by RSSHub",
      "errorAt": "2025-08-22T22:18:31.012Z",
      "errorMessage": "[GET] \"https://sis001.com/forum/space.php?uid=13131575\": 403 Forbidden\n",
      "id": "54962749776429056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sis001.com/forum/space.php?uid=13131575",
      "title": "weiweix120的主题",
      "type": "feed",
      "url": "rsshub://sis001/author/13131575"
    },
    {
      "description": "duduuuuuuuuuuuu的主题 - Powered by RSSHub",
      "errorAt": "2025-08-22T20:39:45.412Z",
      "errorMessage": "[GET] \"https://sis001.com/forum/space.php?uid=13425114\": 403 Forbidden\n[GET] \"https://sis001.com/forum/space.php?uid=13425114\": 403 Forbidden\n",
      "id": "150102738154936320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sis001.com/forum/space.php?uid=13425114",
      "title": "duduuuuuuuuuuuu的主题",
      "type": "feed",
      "url": "rsshub://sis001/author/13425114"
    }
  ]
}
```
