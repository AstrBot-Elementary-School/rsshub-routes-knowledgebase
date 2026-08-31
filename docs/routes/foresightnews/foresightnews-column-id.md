# Foresight News - 专栏

## Coverage
`index-only`

## Route
- Namespace: `foresightnews`
- Namespace Name: `Foresight News`
- Route Path: `/foresightnews/column/:id`
- Route Name: `专栏`
- Example: `/foresightnews/column/1`
- URL: `foresightnews.pro/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 专栏 id, 可在对应专栏页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `foresightnews.pro/column/detail/:id`
  - `foresightnews.pro/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/foresightnews/column/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 63,
  "location": "column.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专栏",
  "parameters": {
    "id": "专栏 id, 可在对应专栏页 URL 中找到"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "foresightnews.pro/column/detail/:id",
        "foresightnews.pro/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "ForesightNews 深度 - Foresight News - Powered by RSSHub",
      "errorAt": "2026-08-22T17:25:24.780Z",
      "errorMessage": "browserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "56166789173943296",
      "image": "https://img.foresightnews.pro/vertical_logo.png",
      "ownerUserId": null,
      "siteUrl": "https://foresightnews.pro/column/detail/894",
      "title": "Foresight News - ForesightNews 深度",
      "type": "feed",
      "url": "rsshub://foresightnews/column/894"
    },
    {
      "description": "ForesightNews 独家 - Foresight News - Powered by RSSHub",
      "errorAt": "2026-03-25T07:03:01.055Z",
      "errorMessage": "[GET] \"https://api.foresightnews.pro/v1/articles?size=50&column_id=1\": 403 Forbidden\n",
      "id": "49357965468513280",
      "image": "https://img.foresightnews.pro/vertical_logo.png",
      "ownerUserId": null,
      "siteUrl": "https://foresightnews.pro/column/detail/1",
      "title": "Foresight News - ForesightNews 独家",
      "type": "feed",
      "url": "rsshub://foresightnews/column/1"
    }
  ],
  "url": "foresightnews.pro/"
}
```
