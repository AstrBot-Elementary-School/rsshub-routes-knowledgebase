# C114 通信网 - 滚动资讯

## Coverage
`index-only`

## Route
- Namespace: `c114`
- Namespace Name: `C114 通信网`
- Route Path: `/c114/roll/:original?`
- Route Name: `滚动资讯`
- Example: `/c114/roll`
- URL: `c114.com.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `roll.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `original`: 只看原创，可选 true 和 false，默认为 false


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `c114.com.cn/news/roll.asp`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "",
  "example": "/c114/roll",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 58,
  "location": "roll.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "滚动资讯",
  "parameters": {
    "original": "只看原创，可选 true 和 false，默认为 false"
  },
  "path": "/roll/:original?",
  "radar": [
    {
      "source": [
        "c114.com.cn/news/roll.asp"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "C114是中国较早成立的专业通信行业垂直门户网站，是中国通信领域历史较久、规模较大、覆盖面较广的网络媒体。C114通信网全面、及时报道包括中国移动、电信、联通、华为、中兴、爱立信等国内外运营商、设备商资讯以及行业新动态；C114通信人家园是国内较大的通信专业社区。 - Powered by RSSHub",
      "errorAt": "2026-08-26T01:30:39.209Z",
      "errorMessage": "Failed to fetch\nFailed to fetch\n[GET] \"https://www.c114.com.cn/news/roll.asp\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 113.215.230.105:443, 113.215.230.101:443, 113.215.230.106:443, 113.215.230.104:443, 113.215.230.103:443, 113.215.230.100:443, 113.215.230.102:443, 113.215.230.99:443, timeout: 10000ms))\n",
      "id": "55939235463397378",
      "image": "https://www.c114.com.cn/images/18/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.c114.com.cn/news/roll.asp",
      "title": "滚动资讯 - C114通信网",
      "type": "feed",
      "url": "rsshub://c114/roll"
    },
    {
      "description": "C114是中国较早成立的专业通信行业垂直门户网站，是中国通信领域历史较久、规模较大、覆盖面较广的网络媒体。C114通信网全面、及时报道包括中国移动、电信、联通、华为、中兴、爱立信等国内外运营商、设备商资讯以及行业新动态；C114通信人家园是国内较大的通信专业社区。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76795492369210368",
      "image": "https://www.c114.com.cn/images/18/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.c114.com.cn/news/roll.asp",
      "title": "滚动资讯 - C114通信网",
      "type": "feed",
      "url": "rsshub://c114/roll/:original"
    }
  ],
  "url": "c114.com.cn"
}
```
