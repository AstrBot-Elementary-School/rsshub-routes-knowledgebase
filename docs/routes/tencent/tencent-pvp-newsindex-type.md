# 腾讯 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `tencent`
- Namespace Name: `腾讯`
- Route Path: `/tencent/pvp/newsindex/:type`
- Route Name: `新闻中心`
- Example: `/tencent/pvp/newsindex/all`
- URL: `tencent.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `Jeason0228, HenryQW`
- Source Location: `pvp/newsindex.ts`
- Source Module: `_None_`

## Description
| 全部 | 热门 | 新闻 | 公告 | 活动 | 赛事 | 优化 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| all  | rm   | xw   | gg   | hd   | ss   | yh   |

## Parameters
- `type`: 栏目分类，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 全部 | 热门 | 新闻 | 公告 | 活动 | 赛事 | 优化 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| all  | rm   | xw   | gg   | hd   | ss   | yh   |",
  "example": "/tencent/pvp/newsindex/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "pvp/newsindex.ts",
  "maintainers": [
    "Jeason0228",
    "HenryQW"
  ],
  "name": "新闻中心",
  "parameters": {
    "type": "栏目分类，见下表"
  },
  "path": "/pvp/newsindex/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(12) ] to not include 'https://pvp.qq.com/web201706/newsdeta…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "《王者荣耀》是腾讯天美工作室历时3年推出的东方英雄即时对战手游大作，抗塔强杀、团灭超神，领略爽热血竞技的酣畅淋漓！1v1、3v3、闯关等丰富游戏模式，随时战，更自由！跨服匹配秒开局，好友组队战排位，不靠装备、没有等级，更公平、更爽快的无差异对战！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63214823163257856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pvp.qq.com/web201706/newsindex.shtml",
      "title": "【全部】 - 王者荣耀 - 新闻列表",
      "type": "feed",
      "url": "rsshub://tencent/pvp/newsindex/all"
    },
    {
      "description": "《王者荣耀》是腾讯天美工作室历时3年推出的东方英雄即时对战手游大作，抗塔强杀、团灭超神，领略爽热血竞技的酣畅淋漓！1v1、3v3、闯关等丰富游戏模式，随时战，更自由！跨服匹配秒开局，好友组队战排位，不靠装备、没有等级，更公平、更爽快的无差异对战！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63215511065306112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pvp.qq.com/web201706/newsindex.shtml",
      "title": "【热门】 - 王者荣耀 - 新闻列表",
      "type": "feed",
      "url": "rsshub://tencent/pvp/newsindex/rm"
    }
  ]
}
```
