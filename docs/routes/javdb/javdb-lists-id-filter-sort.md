# JavDB - 清单

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/javdb/lists/:id/:filter?/:sort?`
- Route Name: `清单`
- Example: `/javdb/lists/2GPgB`
- URL: `javdb.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `dddepg`
- Source Location: `lists.ts`
- Source Module: `_None_`

## Description
过滤

| 全部 | 占位 | 可播放   | 單體作品 | 含磁链   | 含字幕 | 預覽圖  |
| ---- | ---- | -------- | -------- | -------- | ------ | ------- |
|      | none | playable | single   | download | cnsub  | preview |

排序

| 加入时间排序 | 发布时间排序 |
| ------------ | ------------ |
| 0            | 1            |

## Parameters
- `id`: 编号，可在清单页 URL 中找到
- `filter`: 过滤，见下表，默认为 `全部`，需要占位时可设置为 `none`
- `sort`: 排序，见下表，默认为 `加入时间排序`


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javdb.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "过滤\n\n| 全部 | 占位 | 可播放   | 單體作品 | 含磁链   | 含字幕 | 預覽圖  |\n| ---- | ---- | -------- | -------- | -------- | ------ | ------- |\n|      | none | playable | single   | download | cnsub  | preview |\n\n排序\n\n| 加入时间排序 | 发布时间排序 |\n| ------------ | ------------ |\n| 0            | 1            |",
  "example": "/javdb/lists/2GPgB",
  "features": {
    "nsfw": true
  },
  "heat": 47,
  "location": "lists.ts",
  "maintainers": [
    "dddepg"
  ],
  "name": "清单",
  "parameters": {
    "filter": "过滤，见下表，默认为 `全部`，需要占位时可设置为 `none`",
    "id": "编号，可在清单页 URL 中找到",
    "sort": "排序，见下表，默认为 `加入时间排序`"
  },
  "path": "/lists/:id/:filter?/:sort?",
  "radar": [
    {
      "source": [
        "javdb.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "神片列表 - JavDB 加入时间排序 - Powered by RSSHub",
      "errorAt": "2026-08-23T09:52:34.488Z",
      "errorMessage": "Failed to fetch\n530 \nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "129737927519721472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/lists/gVQq?lst=0",
      "title": "神片列表 - JavDB 加入时间排序",
      "type": "feed",
      "url": "rsshub://javdb/lists/gVQq"
    },
    {
      "description": "幼嫩白涩 - JavDB 加入时间排序 - Powered by RSSHub",
      "errorAt": "2026-08-22T01:18:54.232Z",
      "errorMessage": "530 \nFailed to fetch\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "129738038308376576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/lists/ZdrJv?lst=0",
      "title": "幼嫩白涩 - JavDB 加入时间排序",
      "type": "feed",
      "url": "rsshub://javdb/lists/ZdrJv"
    }
  ],
  "url": "javdb.com/"
}
```
