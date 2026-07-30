# 鹰角网络 - 明日方舟 - 游戏内公告

## Coverage
`index-only`

## Route
- Namespace: `hypergryph`
- Namespace Name: `鹰角网络`
- Route Path: `/hypergryph/arknights/announce/:platform?/:group?`
- Route Name: `明日方舟 - 游戏内公告`
- Example: `/hypergryph/arknights/announce`
- URL: `www.hypergryph.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `swwind`
- Source Location: `arknights/announce.ts`
- Source Module: `_None_`

## Description
平台

|  安卓服 | iOS 服 |   B 服   |
| :-----: | :----: | :------: |
| Android |   IOS  | Bilibili |

分组

| 全部 | 系统公告 | 活动公告 |
| :--: | :------: | :------: |
|  ALL |  SYSTEM  | ACTIVITY |

## Parameters
- `platform`: 平台，默认为 Android
- `group`: 分组，默认为 ALL


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "平台\n\n|  安卓服 | iOS 服 |   B 服   |\n| :-----: | :----: | :------: |\n| Android |   IOS  | Bilibili |\n\n分组\n\n| 全部 | 系统公告 | 活动公告 |\n| :--: | :------: | :------: |\n|  ALL |  SYSTEM  | ACTIVITY |",
  "example": "/hypergryph/arknights/announce",
  "heat": 36,
  "location": "arknights/announce.ts",
  "maintainers": [
    "swwind"
  ],
  "name": "明日方舟 - 游戏内公告",
  "parameters": {
    "group": "分组，默认为 ALL",
    "platform": "平台，默认为 Android"
  },
  "path": "/arknights/announce/:platform?/:group?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected -4487620597 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "《明日方舟》全部公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41374862675304448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ak.hypergryph.com/",
      "title": "《明日方舟》全部公告",
      "type": "feed",
      "url": "rsshub://hypergryph/arknights/announce"
    },
    {
      "description": "《明日方舟》全部公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "159622024157116416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ak.hypergryph.com/",
      "title": "《明日方舟》全部公告",
      "type": "feed",
      "url": "rsshub://hypergryph/arknights/announce/Android/ALL"
    }
  ]
}
```
