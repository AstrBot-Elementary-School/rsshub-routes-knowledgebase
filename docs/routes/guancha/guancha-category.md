# 观察者网 - 首页

## Coverage
`index-only`

## Route
- Namespace: `guancha`
- Namespace Name: `观察者网`
- Route Path: `/guancha/:category?`
- Route Name: `首页`
- Example: `/guancha`
- URL: `guancha.cn/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk, Jeason0228`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 全部 | 评论 & 研究 | 要闻  | 风闻    | 热点新闻 | 滚动新闻 |
| ---- | ----------- | ----- | ------- | -------- | -------- |
| all  | review      | story | fengwen | redian   | gundong  |

home = 评论 & 研究 + 要闻 + 风闻

others = 热点新闻 + 滚动新闻

::: tip
观察者网首页左中右的三个 column 分别对应 **评论 & 研究**、**要闻**、**风闻** 三个部分。
:::

## Parameters
- `category`: 分类，见下表，默认为全部


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
  - `guancha.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 全部 | 评论 & 研究 | 要闻  | 风闻    | 热点新闻 | 滚动新闻 |\n| ---- | ----------- | ----- | ------- | -------- | -------- |\n| all  | review      | story | fengwen | redian   | gundong  |\n\nhome = 评论 & 研究 + 要闻 + 风闻\n\nothers = 热点新闻 + 滚动新闻\n\n::: tip\n观察者网首页左中右的三个 column 分别对应 **评论 & 研究**、**要闻**、**风闻** 三个部分。\n:::",
  "example": "/guancha",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 332,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "Jeason0228"
  ],
  "name": "首页",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "guancha.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(4) ] to not include 'https://www.guancha.cn/economy/2026_0…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "观察者网 - 全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56875843110895617",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.guancha.cn/",
      "title": "观察者网 - 全部",
      "type": "feed",
      "url": "rsshub://guancha"
    },
    {
      "description": "观察者网 - 评论 & 研究 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83393249384067072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.guancha.cn/",
      "title": "观察者网 - 评论 & 研究",
      "type": "feed",
      "url": "rsshub://guancha/review"
    }
  ],
  "url": "guancha.cn/"
}
```
