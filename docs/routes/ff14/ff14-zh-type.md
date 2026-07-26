# FINAL FANTASY XIV - 最终幻想 14 国服

## Coverage
`index-only`

## Route
- Namespace: `ff14`
- Namespace Name: `FINAL FANTASY XIV`
- Route Path: `/ff14/zh/:type?`
- Route Name: `最终幻想 14 国服`
- Example: `/ff14/zh/news`
- URL: `ff.web.sdo.com/web8/index.html`
- Language: `_None_`
- Categories: `game`
- Maintainers: `Kiotlin, ZeroClad, 15x15G`
- Source Location: `ff14-zh.ts`
- Source Module: `_None_`

## Description
| 新闻 | 公告     | 活动   | 广告      | 所有 |
| ---- | -------- | ------ | --------- | ---- |
| news | announce | events | advertise | all  |

## Parameters
- `type`: 分类名，预设为 `all`


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
  - `ff.web.sdo.com/web8/index.html`
- `target`: `/zh`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 新闻 | 公告     | 活动   | 广告      | 所有 |\n| ---- | -------- | ------ | --------- | ---- |\n| news | announce | events | advertise | all  |",
  "example": "/ff14/zh/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "ff14-zh.ts",
  "maintainers": [
    "Kiotlin",
    "ZeroClad",
    "15x15G"
  ],
  "name": "最终幻想 14 国服",
  "parameters": {
    "type": "分类名，预设为 `all`"
  },
  "path": [
    "/zh/:type?",
    "/ff14_zh/:type?"
  ],
  "radar": [
    {
      "source": [
        "ff.web.sdo.com/web8/index.html"
      ],
      "target": "/zh"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(27) ] to not include 'https://ff.sdo.com/web8/555'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "《最终幻想14》是史克威尔艾尼克斯出品的全球经典游戏品牌FINAL FANTASY系列的最新作品，IGN获得9.2高分！全球累计用户突破1600万！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58939975768068096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ff.sdo.com/web8/index.html#/newstab/newslist",
      "title": "最终幻想14（国服）新闻中心",
      "type": "feed",
      "url": "rsshub://ff14/zh/news"
    },
    {
      "description": "《最终幻想14》是史克威尔艾尼克斯出品的全球经典游戏品牌FINAL FANTASY系列的最新作品，IGN获得9.2高分！全球累计用户突破1600万！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84969277213600768",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ff.sdo.com/web8/index.html#/newstab/newslist",
      "title": "最终幻想14（国服）新闻中心",
      "type": "feed",
      "url": "rsshub://ff14/zh"
    }
  ],
  "url": "ff.web.sdo.com/web8/index.html"
}
```
