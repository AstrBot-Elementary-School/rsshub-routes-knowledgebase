# 環球唱片(香港)官方網上商店 - HKU Shop 黑胶专区

## Coverage
`index-only`

## Route
- Namespace: `hkushop`
- Namespace Name: `環球唱片(香港)官方網上商店`
- Route Path: `/hkushop/vinyl/:cat?`
- Route Name: `HKU Shop 黑胶专区`
- Example: `/hkushop/vinyl`
- URL: `hkushop.com/vinyl-or-picture-lp.html`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `gideonsenku`
- Source Location: `vinyl-or-picture-lp.ts`
- Source Module: `_None_`

## Description
常见分类:

| 華語音樂 | 經典復刻 | 古典跨界 | 爵士音樂 | 國際音樂 | 電影原聲帶 | 黑膠日本音樂 |
| -------- | -------- | -------- | -------- | -------- | ---------- | ------------ |
| 37       | 38       | 40       | 41       | 39       | 170        | 224          |

## Parameters
- `cat`: 分类，见下表，默认不分类


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `hkushop.com/vinyl-or-picture-lp.html`
  - `hkushop.com/`
- `target`: `/vinyl`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "常见分类:\n\n| 華語音樂 | 經典復刻 | 古典跨界 | 爵士音樂 | 國際音樂 | 電影原聲帶 | 黑膠日本音樂 |\n| -------- | -------- | -------- | -------- | -------- | ---------- | ------------ |\n| 37       | 38       | 40       | 41       | 39       | 170        | 224          |",
  "example": "/hkushop/vinyl",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 3,
  "location": "vinyl-or-picture-lp.ts",
  "maintainers": [
    "gideonsenku"
  ],
  "name": "HKU Shop 黑胶专区",
  "parameters": {
    "cat": "分类，见下表，默认不分类"
  },
  "path": "/vinyl/:cat?",
  "radar": [
    {
      "source": [
        "hkushop.com/vinyl-or-picture-lp.html",
        "hkushop.com/"
      ],
      "target": "/vinyl"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "HKU Shop 黑胶唱片最新商品信息 - Powered by RSSHub",
      "errorAt": "2026-03-05T08:51:25.274Z",
      "errorMessage": "browserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "125428127328664576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hkushop.com/vinyl-or-picture-lp.html",
      "title": "黑胶彩胶系列 - HKU Shop 环球唱片网店",
      "type": "feed",
      "url": "rsshub://hkushop/vinyl"
    }
  ],
  "url": "hkushop.com/vinyl-or-picture-lp.html"
}
```
