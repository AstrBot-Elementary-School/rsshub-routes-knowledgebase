# Perplexity - Changelog

## Coverage
`index-only`

## Route
- Namespace: `perplexity`
- Namespace Name: `Perplexity`
- Route Path: `/perplexity/changelog`
- Route Name: `Changelog`
- Example: `/perplexity/changelog`
- URL: `www.perplexity.ai`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `xbot`
- Source Location: `changelog.ts`
- Source Module: `_None_`

## Description
Subscribe to Perplexity changelog for latest updates and releases.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.perplexity.ai/changelog`
- `target`: `/changelog`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "Subscribe to Perplexity changelog for latest updates and releases.",
  "example": "/perplexity/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 9,
  "location": "changelog.ts",
  "maintainers": [
    "xbot"
  ],
  "name": "Changelog",
  "path": "/changelog",
  "radar": [
    {
      "source": [
        "www.perplexity.ai/changelog"
      ],
      "target": "/changelog"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Stay up to date with what’s new in Perplexity. The changelog highlights the latest features, improvements, and experiments, so you can get the most out of Perplexity as it gets better every week. - Powered by RSSHub",
      "errorAt": "2026-08-22T12:13:01.180Z",
      "errorMessage": "browserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "241365598746245120",
      "image": "https://frontend-cdn.perplexity.ai/_agi_assets/marketing/hub/hub-og-image.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.perplexity.ai/changelog",
      "title": "Perplexity Changelog",
      "type": "feed",
      "url": "rsshub://perplexity/changelog"
    }
  ],
  "url": "www.perplexity.ai",
  "view": 0
}
```
