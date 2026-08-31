# 东方财富 - 个人中心评论

## Coverage
`index-only`

## Route
- Namespace: `eastmoney`
- Namespace Name: `东方财富`
- Route Path: `/eastmoney/gerenzhongxin/trpl/:uid`
- Route Name: `个人中心评论`
- Example: `/eastmoney/gerenzhongxin/trpl/2922094262312522`
- URL: `data.eastmoney.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `AwesomeDog`
- Source Location: `gerenzhongxin/trpl.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户id,即用户主页网址末尾的数字


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
  - `guba.eastmoney.com`
### Rule 2
- `source`:
  - `caifuhao.eastmoney.com`
### Rule 3
- `source`:
  - `i.eastmoney.com/:uid`
- `target`: `/gerenzhongxin/trpl/:uid`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/eastmoney/gerenzhongxin/trpl/2922094262312522",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "gerenzhongxin/trpl.ts",
  "maintainers": [
    "AwesomeDog"
  ],
  "name": "个人中心评论",
  "parameters": {
    "uid": "用户id,即用户主页网址末尾的数字"
  },
  "path": "/gerenzhongxin/trpl/:uid",
  "radar": [
    {
      "source": [
        "guba.eastmoney.com"
      ]
    },
    {
      "source": [
        "caifuhao.eastmoney.com"
      ]
    },
    {
      "source": [
        "i.eastmoney.com/:uid"
      ],
      "target": "/gerenzhongxin/trpl/:uid"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(12) ] to not include 'guid-77135ef210e3717af288497a67f07ed0…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "view": 0
}
```
