# Reuters - Inverstigates

## Coverage
`index-only`

## Route
- Namespace: `reuters`
- Namespace Name: `Reuters`
- Route Path: `/reuters/investigates`
- Route Name: `Inverstigates`
- Example: `/reuters/investigates`
- URL: `reuters.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `LyleLee`
- Source Location: `investigates.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
    "traditional-media"
  ],
  "example": "/reuters/investigates",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 228,
  "location": "investigates.ts",
  "maintainers": [
    "LyleLee"
  ],
  "name": "Inverstigates",
  "parameters": {},
  "path": "/investigates",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Special Reports from Reuters journalists around the world - Powered by RSSHub",
      "errorAt": "2025-07-29T12:13:51.981Z",
      "errorMessage": "Authentication failed. Access denied.\n/reuters/investigates\n[GET] \"https://www.reuters.com/investigates/\": 401 HTTP Forbidden\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "55135298544041995",
      "image": "https://www.reuters.com/pf/resources/images/reuters/logo-vertical-default-512x512.png?d=116",
      "ownerUserId": null,
      "siteUrl": "https://www.reuters.com/investigates/",
      "title": "Special Reports from Reuters journalists around the world | Reuters",
      "type": "feed",
      "url": "rsshub://reuters/investigates"
    }
  ],
  "view": 0
}
```
