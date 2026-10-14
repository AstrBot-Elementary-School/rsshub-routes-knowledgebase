# iRead 趣读 - 盐选故事专栏

## Coverage
`index-only`

## Route
- Namespace: `ifun`
- Namespace Name: `iRead 趣读`
- Route Path: `/ifun/n/tag/:name`
- Route Name: `盐选故事专栏`
- Example: `/ifun/n/tag/zhihu`
- URL: `iread.life`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `n/tag.ts`
- Source Module: `_None_`

## Description
例如 [zhihu 故事集](https://iread.life/tag/zhihu) 对应 `/ifun/n/tag/zhihu`。更多故事集请见 [iRead 故事集](https://iread.life/tag)。

## Parameters
- `name`: 故事集名称，可在对应故事集页 URL 的 /tag/ 后找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `iread.life/tag/:name`
- `target`: `/n/tag/:name`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "例如 [zhihu 故事集](https://iread.life/tag/zhihu) 对应 `/ifun/n/tag/zhihu`。更多故事集请见 [iRead 故事集](https://iread.life/tag)。",
  "example": "/ifun/n/tag/zhihu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "n/tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "盐选故事专栏",
  "parameters": {
    "name": "故事集名称，可在对应故事集页 URL 的 /tag/ 后找到"
  },
  "path": "/n/tag/:name",
  "radar": [
    {
      "source": [
        "iread.life/tag/:name"
      ],
      "target": "/n/tag/:name"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "zhihu - Powered by RSSHub",
      "errorAt": "2025-01-19T19:00:03.264Z",
      "errorMessage": "Cannot read properties of undefined (reading 'records')\n",
      "id": "88803144626877440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://n.ifun.cool/article-list/1?tagName=zhihu",
      "title": "趣集 - zhihu",
      "type": "feed",
      "url": "rsshub://ifun/n/tag/zhihu"
    },
    {
      "description": ":name - Powered by RSSHub",
      "errorAt": "2024-12-27T08:10:00.277Z",
      "errorMessage": "Cannot read properties of undefined (reading 'records')\n",
      "id": "86762794364010496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://n.ifun.cool/article-list/1?tagName=:name",
      "title": "趣集 - :name",
      "type": "feed",
      "url": "rsshub://ifun/n/tag/:name"
    }
  ],
  "url": "iread.life",
  "view": 0
}
```
