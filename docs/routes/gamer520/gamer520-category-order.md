# 全球游戏交流中心 - 文章

## Coverage
`index-only`

## Route
- Namespace: `gamer520`
- Namespace Name: `全球游戏交流中心`
- Route Path: `/gamer520/:category?/:order?`
- Route Name: `文章`
- Example: `/gamer520/switchyouxi`
- URL: `www.gamer520.com/`
- Language: `_None_`
- Categories: `game`
- Maintainers: `xzzpig`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
分类

| 所有 | Switch 游戏下载 | 金手指     | 3A 巨作 | switch 主题 | PC 游戏 |
| ---- | --------------- | ---------- | ------- | ----------- | ------- |
| all  | switchyouxi     | jinshouzhi | 3ajuzuo | zhuti       | pcgame  |

## Parameters
- `category`: 分类，见下表
- `order`: 排序，发布日期: date; 修改日期: modified


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "分类\n\n| 所有 | Switch 游戏下载 | 金手指     | 3A 巨作 | switch 主题 | PC 游戏 |\n| ---- | --------------- | ---------- | ------- | ----------- | ------- |\n| all  | switchyouxi     | jinshouzhi | 3ajuzuo | zhuti       | pcgame  |",
  "example": "/gamer520/switchyouxi",
  "features": {
    "antiCrawler": true
  },
  "heat": 111,
  "location": "index.ts",
  "maintainers": [
    "xzzpig"
  ],
  "name": "文章",
  "parameters": {
    "category": "分类，见下表",
    "order": "排序，发布日期: date; 修改日期: modified"
  },
  "path": "/:category?/:order?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "全球游戏交流中心-所有 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78689933854680064",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gamer520.com/",
      "title": "全球游戏交流中心-所有",
      "type": "feed",
      "url": "rsshub://gamer520/all"
    },
    {
      "description": "全球游戏交流中心-所有 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "153752488543499264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gamer520.com/",
      "title": "全球游戏交流中心-所有",
      "type": "feed",
      "url": "rsshub://gamer520"
    }
  ],
  "url": "www.gamer520.com/"
}
```
