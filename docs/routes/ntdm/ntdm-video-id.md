# NT动漫 - 番剧详情

## Coverage
`index-only`

## Route
- Namespace: `ntdm`
- Namespace Name: `NT动漫`
- Route Path: `/ntdm/video/:id`
- Route Name: `番剧详情`
- Example: `/ntdm/video/4309`
- URL: `www.ntdm9.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `Yamico`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 番剧 id，对应详情 URL 中找到


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
  - `ntdm9.com/video/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/ntdm/video/4309",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "video.ts",
  "maintainers": [
    "Yamico"
  ],
  "name": "番剧详情",
  "parameters": {
    "id": "番剧 id，对应详情 URL 中找到"
  },
  "path": "/video/:id",
  "radar": [
    {
      "source": [
        "ntdm9.com/video/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
