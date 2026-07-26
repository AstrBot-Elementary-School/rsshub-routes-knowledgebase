# COMIC FUZ - 漫画详情

## Coverage
`index-only`

## Route
- Namespace: `comic-fuz`
- Namespace Name: `COMIC FUZ`
- Route Path: `/comic-fuz/manga/:id`
- Route Name: `漫画详情`
- Example: `/comic-fuz/manga/218`
- URL: `comic-fuz.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `xiaobailoves`
- Source Location: `manga.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: ComicFuz中对应的漫画id


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
  - `comic-fuz.com/manga/:id`
- `target`: `/manga/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comic-fuz/manga/218",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "manga.ts",
  "maintainers": [
    "xiaobailoves"
  ],
  "name": "漫画详情",
  "parameters": {
    "id": "ComicFuz中对应的漫画id"
  },
  "path": "/manga/:id",
  "radar": [
    {
      "source": [
        "comic-fuz.com/manga/:id"
      ],
      "target": "/manga/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -513768976 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
