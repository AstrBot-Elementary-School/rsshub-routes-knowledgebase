# Bluesky (bsky) - Keywords

## Coverage
`index-only`

## Route
- Namespace: `bsky`
- Namespace Name: `Bluesky (bsky)`
- Route Path: `/bsky/keyword/:keyword`
- Route Name: `Keywords`
- Example: `/bsky/keyword/hello`
- URL: `bsky.app`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `untitaker, DIYgod`
- Source Location: `keyword.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: N


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
    "social-media"
  ],
  "example": "/bsky/keyword/hello",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 41,
  "location": "keyword.ts",
  "maintainers": [
    "untitaker",
    "DIYgod"
  ],
  "name": "Keywords",
  "parameters": {
    "keyword": "N"
  },
  "path": "/keyword/:keyword",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Bluesky Keyword - 财经 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "167786476135939072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bsky.app/search?q=%E8%B4%A2%E7%BB%8F",
      "title": "Bluesky Keyword - 财经",
      "type": "feed",
      "url": "rsshub://bsky/keyword/%E8%B4%A2%E7%BB%8F"
    },
    {
      "description": "Bluesky Keyword - 习近平 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "168513684017369088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bsky.app/search?q=%E4%B9%A0%E8%BF%91%E5%B9%B3",
      "title": "Bluesky Keyword - 习近平",
      "type": "feed",
      "url": "rsshub://bsky/keyword/%E4%B9%A0%E8%BF%91%E5%B9%B3"
    }
  ]
}
```
