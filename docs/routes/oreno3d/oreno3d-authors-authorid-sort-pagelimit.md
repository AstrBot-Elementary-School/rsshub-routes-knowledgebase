# 俺の 3D エロ動画 (oreno3d) - Author Search

## Coverage
`index-only`

## Route
- Namespace: `oreno3d`
- Namespace Name: `俺の 3D エロ動画 (oreno3d)`
- Route Path: `/oreno3d/authors/:authorid/:sort/:pagelimit?`
- Route Name: `Author Search`
- Example: `/oreno3d/authors/3189/latest/1`
- URL: `oreno3d.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `xueli_sherryli`
- Source Location: `main.tsx`
- Source Module: `_None_`

## Description
| favorites | hot | latest | popularity |
| --------- | --- | ------ | ---------- |
| favorites | hot | latest | popularity |

## Parameters
- `authorid`: Author id, can be found in URL
- `sort`: Sort method, see the table above
- `pagelimit`: The maximum number of pages to be crawled, the default is 1


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
    "anime"
  ],
  "description": "| favorites | hot | latest | popularity |\n| --------- | --- | ------ | ---------- |\n| favorites | hot | latest | popularity |",
  "example": "/oreno3d/authors/3189/latest/1",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 23,
  "location": "main.tsx",
  "maintainers": [
    "xueli_sherryli"
  ],
  "name": "Author Search",
  "parameters": {
    "authorid": "Author id, can be found in URL",
    "pagelimit": "The maximum number of pages to be crawled, the default is 1",
    "sort": "Sort method, see the table above"
  },
  "path": [
    "/authors/:authorid/:sort/:pagelimit?",
    "/characters/:characterid/:sort/:pagelimit?",
    "/origins/:originid/:sort/:pagelimit?",
    "/search/:keyword/:sort/:pagelimit?",
    "/tags/:tagid/:sort/:pagelimit?"
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Mister Pinkの3Dエロ動画・エロMMD・エロアニメ一覧｜俺の3Dエロ動画 - 新着(Page 1-1) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61611245193032704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://oreno3d.com/authors/3189?sort=latest",
      "title": "Mister Pinkの3Dエロ動画・エロMMD・エロアニメ一覧｜俺の3Dエロ動画 - 新着(Page 1-1)",
      "type": "feed",
      "url": "rsshub://oreno3d/authors/3189/latest/1"
    }
  ]
}
```
