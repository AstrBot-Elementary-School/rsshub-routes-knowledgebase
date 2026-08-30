# 雪球 - 股票信息

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/stock_info/:id/:type?`
- Route Name: `股票信息`
- Example: `/xueqiu/stock_info/SZ000002`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `YuYang`
- Source Location: `stock-info.ts`
- Source Module: `_None_`

## Description
| 全部 | 讨论    | 交易  | 资讯 | 公告         |
| ---- | ------- | ----- | ---- | ------------ |
| all  | discuss | trans | news | announcement |

## Parameters
- `id`: 股票代码（需要带上交易所）
- `type`: 动态的类型, 不填则为股票公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xueqiu.com/S/:id`
  - `xueqiu.com/s/:id`
- `target`: `/stock_info/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 全部 | 讨论    | 交易  | 资讯 | 公告         |\n| ---- | ------- | ----- | ---- | ------------ |\n| all  | discuss | trans | news | announcement |",
  "example": "/xueqiu/stock_info/SZ000002",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 50,
  "location": "stock-info.ts",
  "maintainers": [
    "YuYang"
  ],
  "name": "股票信息",
  "parameters": {
    "id": "股票代码（需要带上交易所）",
    "type": "动态的类型, 不填则为股票公告"
  },
  "path": "/stock_info/:id/:type?",
  "radar": [
    {
      "source": [
        "xueqiu.com/S/:id",
        "xueqiu.com/s/:id"
      ],
      "target": "/stock_info/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "兆易创新 - 资讯 - Powered by RSSHub",
      "errorAt": "2026-08-22T10:36:09.282Z",
      "errorMessage": "browserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "64923928046286858",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/S/SH603986",
      "title": "SH603986 兆易创新 - 资讯",
      "type": "feed",
      "url": "rsshub://xueqiu/stock_info/SH603986/news"
    },
    {
      "description": "豪威集团 - 公告 - Powered by RSSHub",
      "errorAt": "2026-08-22T05:33:23.795Z",
      "errorMessage": "browserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "64923928046286863",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/S/SH603501",
      "title": "SH603501 豪威集团 - 公告",
      "type": "feed",
      "url": "rsshub://xueqiu/stock_info/SH603501"
    }
  ]
}
```
