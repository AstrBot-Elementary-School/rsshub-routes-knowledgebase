# JavDB - 演員

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/javdb/actors/:id/:filter?`
- Route Name: `演員`
- Example: `/javdb/actors/R2Vg`
- URL: `javdb.com/`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `nczitzk`
- Source Location: `actors.ts`
- Source Module: `_None_`

## Description
| 全部 | 可播放 | 單體作品 | 可下載 | 含字幕 |
| ---- | ------ | -------- | ------ | ------ |
|      | p      | s        | d      | c      |

所有演员编号参见 [演員庫](https://javdb.com/actors)

可用 addon\_tags 参数添加额外的过滤 tag，可从网页 url 中获取，例如 `/javdb/actors/R2Vg?addon_tags=212,18` 可筛选 `VR` 和 `中出`。

## Parameters
- `id`: 编号，可在演员页 URL 中找到
- `filter`: 过滤，见下表，默认为 `全部`


## Features
- `requireConfig`: [{"description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取", "name": "JAVDB_SESSION", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
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
    "multimedia",
    "popular"
  ],
  "description": "| 全部 | 可播放 | 單體作品 | 可下載 | 含字幕 |\n| ---- | ------ | -------- | ------ | ------ |\n|      | p      | s        | d      | c      |\n\n所有演员编号参见 [演員庫](https://javdb.com/actors)\n\n可用 addon\\_tags 参数添加额外的过滤 tag，可从网页 url 中获取，例如 `/javdb/actors/R2Vg?addon_tags=212,18` 可筛选 `VR` 和 `中出`。",
  "example": "/javdb/actors/R2Vg",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取",
        "name": "JAVDB_SESSION",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4878,
  "location": "actors.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "演員",
  "parameters": {
    "filter": "过滤，见下表，默认为 `全部`",
    "id": "编号，可在演员页 URL 中找到"
  },
  "path": "/actors/:id/:filter?",
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
      "description": "桃乃木かな - JavDB - Powered by RSSHub",
      "errorAt": "2026-09-02T09:14:11.409Z",
      "errorMessage": "Failed to fetch\n530 \nInvalid RSSHub JSON Feed from 98292582055262208\nbrowserType.launch: Executable doesn't exist at /root/.cache/ms-playwright/chromium_headless_shell-1234/chrome-headless-shell-linux64/chrome-headless-shell\n╔════════════════════════════════════════════════════════════╗\n║ Looks like Playwright was just installed or updated.       ║\n║ Please run the following command to download new browsers: ║\n║                                                            ║\n║     npx playwright install                                 ║\n║                                                            ║\n║ <3 Patchright Team                                         ║\n╚════════════════════════════════════════════════════════════╝\nFailed to fetch\n[GET] \"https://javdb.com/v/Mb4WXX\": 429 Too Many Requests\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "58137945200229376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/actors/0dKX",
      "title": "桃乃木かな - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/actors/0dKX"
    },
    {
      "description": "Kawakita Saika - JavDB - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59231069957378048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/actors/EvkJ",
      "title": "Kawakita Saika - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/actors/EvkJ"
    }
  ],
  "url": "javdb.com/"
}
```
