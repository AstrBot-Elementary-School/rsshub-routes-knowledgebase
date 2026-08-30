# 天下雜誌 - 作者

## Coverage
`index-only`

## Route
- Namespace: `cw`
- Namespace Name: `天下雜誌`
- Route Path: `/cw/author/:channel`
- Route Name: `作者`
- Example: `/cw/author/57`
- URL: `cw.com.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channel`: 作者 ID，可在 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cw.com.tw/author/:channel`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cw/author/57",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "author.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "作者",
  "parameters": {
    "channel": "作者 ID，可在 URL 中找到"
  },
  "path": "/author/:channel",
  "radar": [
    {
      "source": [
        "cw.com.tw/author/:channel"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "《天下雜誌》是《經濟學人》獨家授權的合作媒體。歡迎搜尋Podcast《經濟學人＠天下》，獲得最新一期《經濟學人》獨家解讀。 - Powered by RSSHub",
      "errorAt": "2026-08-23T02:50:24.164Z",
      "errorMessage": "browserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "69435755254558720",
      "image": "https://cdn-www.cw.com.tw/article/201909/article-5d75f21940867.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cw.com.tw/author/57",
      "title": "經濟學人｜最新文章｜天下雜誌",
      "type": "feed",
      "url": "rsshub://cw/author/57"
    }
  ]
}
```
