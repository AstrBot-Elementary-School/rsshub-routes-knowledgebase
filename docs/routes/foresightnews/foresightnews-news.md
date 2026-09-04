# Foresight News - 快讯

## Coverage
`index-only`

## Route
- Namespace: `foresightnews`
- Namespace Name: `Foresight News`
- Route Path: `/foresightnews/news`
- Route Name: `快讯`
- Example: `/foresightnews/news`
- URL: `foresightnews.pro/news`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `foresightnews.pro/news`
  - `foresightnews.pro/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/foresightnews/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 248,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "快讯",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "foresightnews.pro/news",
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
      "description": "快讯 - Foresight News - Powered by RSSHub",
      "errorAt": "2026-08-23T06:15:12.002Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://api.foresightnews.pro/v1/news?size=50\": 403 Forbidden\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "41756176414118912",
      "image": "https://img.foresightnews.pro/vertical_logo.png",
      "ownerUserId": null,
      "siteUrl": "https://foresightnews.pro/news",
      "title": "Foresight News - 快讯",
      "type": "feed",
      "url": "rsshub://foresightnews/news"
    }
  ],
  "url": "foresightnews.pro/news"
}
```
