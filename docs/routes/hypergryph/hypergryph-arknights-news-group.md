# 鹰角网络 - 明日方舟 - 游戏公告与新闻

## Coverage
`index-only`

## Route
- Namespace: `hypergryph`
- Namespace Name: `鹰角网络`
- Route Path: `/hypergryph/arknights/news/:group?`
- Route Name: `明日方舟 - 游戏公告与新闻`
- Example: `/hypergryph/arknights/news`
- URL: `ak-conf.hypergryph.com/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `Astrian`
- Source Location: `arknights/news.ts`
- Source Module: `_None_`

## Description
| 全部 | 最新   | 公告         | 活动     | 新闻 |
| ---- | ------ | ------------ | -------- | ---- |
| ALL  | LATEST | ANNOUNCEMENT | ACTIVITY | NEWS |

## Parameters
- `group`: 分组，默认为 `ALL`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `ak-conf.hypergryph.com/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 全部 | 最新   | 公告         | 活动     | 新闻 |\n| ---- | ------ | ------------ | -------- | ---- |\n| ALL  | LATEST | ANNOUNCEMENT | ACTIVITY | NEWS |",
  "example": "/hypergryph/arknights/news",
  "heat": 21,
  "location": "arknights/news.ts",
  "maintainers": [
    "Astrian"
  ],
  "name": "明日方舟 - 游戏公告与新闻",
  "parameters": {
    "group": "分组，默认为 `ALL`"
  },
  "path": "/arknights/news/:group?",
  "radar": [
    {
      "source": [
        "ak-conf.hypergryph.com/news"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'https://ak.hypergryph.com/news/5104'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "《明日方舟》游戏公告与新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56948849407992834",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ak.hypergryph.com/news",
      "title": "《明日方舟》游戏公告与新闻",
      "type": "feed",
      "url": "rsshub://hypergryph/arknights/news"
    },
    {
      "description": "《明日方舟》游戏公告与新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "197299073968664578",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ak.hypergryph.com/news",
      "title": "《明日方舟》游戏公告与新闻",
      "type": "feed",
      "url": "rsshub://hypergryph/arknights/news/ACTIVITY"
    }
  ],
  "url": "ak-conf.hypergryph.com/news"
}
```
