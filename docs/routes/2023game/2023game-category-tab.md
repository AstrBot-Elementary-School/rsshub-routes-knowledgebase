# 游戏星辰 - 游戏星辰

## Coverage
`index-only`

## Route
- Namespace: `2023game`
- Namespace Name: `游戏星辰`
- Route Path: `/2023game/:category?/:tab?`
- Route Name: `游戏星辰`
- Example: `/2023game/sgame/topicList`
- URL: `www.2023game.com/`
- Language: `_None_`
- Categories: `game`
- Maintainers: `xzzpig`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
分类

| PS4 游戏 | switch 游戏 | 3DS 游戏 | PSV 游戏 | Xbox360   | PS3 游戏 | 世嘉 MD/SS | PSP 游戏    | PC 周边 | 怀旧掌机 | 怀旧主机 | PS4 教程 | PS4 金手指  | switch 金手指  | switch 教程  | switch 补丁   | switch 主题   | switch 存档  |
| -------- | ----------- | -------- | -------- | --------- | -------- | ---------- | ----------- | ------- | -------- | -------- | -------- | ----------- | -------------- | ------------ | ------------- | ------------- | ------------ |
| ps4      | sgame       | 3ds      | psv      | jiaocheng | ps3yx    | zhuji.md   | zhangji.psp | pcgame  | zhangji  | zhuji    | ps4.psjc | ps41.ps4pkg | nsaita.cundang | nsaita.pojie | nsaita.buding | nsaita.zhutie | nsaita.zhuti |

## Parameters
- `category`: 分类，见下表
- `tab`: 标签, 所有:all;最新:topicList;热门:jhcpb


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
  "description": "分类\n\n| PS4 游戏 | switch 游戏 | 3DS 游戏 | PSV 游戏 | Xbox360   | PS3 游戏 | 世嘉 MD/SS | PSP 游戏    | PC 周边 | 怀旧掌机 | 怀旧主机 | PS4 教程 | PS4 金手指  | switch 金手指  | switch 教程  | switch 补丁   | switch 主题   | switch 存档  |\n| -------- | ----------- | -------- | -------- | --------- | -------- | ---------- | ----------- | ------- | -------- | -------- | -------- | ----------- | -------------- | ------------ | ------------- | ------------- | ------------ |\n| ps4      | sgame       | 3ds      | psv      | jiaocheng | ps3yx    | zhuji.md   | zhangji.psp | pcgame  | zhangji  | zhuji    | ps4.psjc | ps41.ps4pkg | nsaita.cundang | nsaita.pojie | nsaita.buding | nsaita.zhutie | nsaita.zhuti |",
  "example": "/2023game/sgame/topicList",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "index.ts",
  "maintainers": [
    "xzzpig"
  ],
  "name": "游戏星辰",
  "parameters": {
    "category": "分类，见下表",
    "tab": "标签, 所有:all;最新:topicList;热门:jhcpb"
  },
  "path": "/:category?/:tab?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "switch游戏下载-免费switch游戏下载-ns游戏资源下载 - 游戏星辰 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75155926100067328",
      "image": "https://www.2023game.com/resources/img/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.2023game.com/sgame/",
      "title": "switch游戏下载-免费switch游戏下载-ns游戏资源下载 - 游戏星辰",
      "type": "feed",
      "url": "rsshub://2023game/sgame/topicList"
    }
  ],
  "url": "www.2023game.com/"
}
```
