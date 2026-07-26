# 客家電視台 - 新聞首頁

## Coverage
`index-only`

## Route
- Namespace: `hakkatv`
- Namespace Name: `客家電視台`
- Route Path: `/hakkatv/news/:type?`
- Route Name: `新聞首頁`
- Example: `/hakkatv/news`
- URL: `hakkatv.org.tw/news`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `type.ts`
- Source Module: `_None_`

## Description
| 客家焦點 | 政經要聞  | 民生醫療 | 地方風采 | 國際萬象      |
| -------- | --------- | -------- | -------- | ------------- |
| hakka    | political | medical  | local    | international |

## Parameters
- `type`: 新聞，見下表，留空為全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hakkatv.org.tw/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 客家焦點 | 政經要聞  | 民生醫療 | 地方風采 | 國際萬象      |\n| -------- | --------- | -------- | -------- | ------------- |\n| hakka    | political | medical  | local    | international |",
  "example": "/hakkatv/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "type.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "新聞首頁",
  "parameters": {
    "type": "新聞，見下表，留空為全部"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "hakkatv.org.tw/news"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'https://www.hakkatv.org.tw/news-detai…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "客家電視是屬於全民、以至於全世界客家族群的頻道，亦是為傳播客家文化而存在，定位為「全體客家族群之媒體」。 - Powered by RSSHub",
      "errorAt": "2026-05-15T19:48:21.195Z",
      "errorMessage": "500 Internal Server Error\n",
      "id": "167304163667564544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hakkatv.org.tw/news",
      "title": "新聞首頁 - 客家電視台",
      "type": "feed",
      "url": "rsshub://hakkatv/news"
    }
  ],
  "url": "hakkatv.org.tw/news"
}
```
