# 米哈游 - 米游社 - 同人榜

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/mihoyo/bbs/img-ranking/:game/:routeParams?`
- Route Name: `米游社 - 同人榜`
- Example: `/mihoyo/bbs/img-ranking/ys/forumType=tongren&cateType=illustration&rankingType=daily`
- URL: `genshin.hoyoverse.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `CaoMeiYouRen`
- Source Location: `bbs/img-ranking.ts`
- Source Module: `_None_`

## Description
| 键          | 含义                                  | 接受的值                                                             | 默认值       |
| ----------- | ------------------------------------- | -------------------------------------------------------------------- | ------------ |
| forumType   | 主榜类型（仅原神、大别野有 cos 主榜） | tongren/cos                                                          | tongren      |
| cateType    | 子榜类型（仅崩坏三、原神有子榜）      | 崩坏三：illustration/comic/cos；原神：illustration/comic/qute/manual | illustration |
| rankingType | 排行榜类型（崩坏二没有日榜）          | daily/weekly/monthly                                                 | daily        |
| lastId      | 当前页 id（用于分页）                 | 数字                                                                 | 1            |

游戏缩写

| 崩坏三 | 原神 | 崩坏二 | 未定事件簿 | 星穹铁道 | 大别野 | 绝区零 |
| ------ | ---- | ------ | ---------- | -------- | ------ | ------ |
| bh3    | ys   | bh2    | wd         | sr       | dby    | zzz    |

主榜类型

| 同人榜  | COS 榜 |
| ------- | ------ |
| tongren | cos    |

子榜类型

崩坏三 子榜

| 插画         | 漫画  | COS |
| ------------ | ----- | --- |
| illustration | comic | cos |

原神 子榜

| 插画         | 漫画  | Q 版 | 手工   |
| ------------ | ----- | ---- | ------ |
| illustration | comic | qute | manual |

排行榜类型

| 日榜  | 周榜   | 月榜    |
| ----- | ------ | ------- |
| daily | weekly | monthly |

## Parameters
- `game`: 游戏缩写
- `routeParams`: 额外参数；请参阅以下说明和表格


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
  - `miyoushe.com/:game/imgRanking/:forum_id/:ranking_id/:cate_id`
- `target`: `/bbs/img-ranking/:game`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 键          | 含义                                  | 接受的值                                                             | 默认值       |\n| ----------- | ------------------------------------- | -------------------------------------------------------------------- | ------------ |\n| forumType   | 主榜类型（仅原神、大别野有 cos 主榜） | tongren/cos                                                          | tongren      |\n| cateType    | 子榜类型（仅崩坏三、原神有子榜）      | 崩坏三：illustration/comic/cos；原神：illustration/comic/qute/manual | illustration |\n| rankingType | 排行榜类型（崩坏二没有日榜）          | daily/weekly/monthly                                                 | daily        |\n| lastId      | 当前页 id（用于分页）                 | 数字                                                                 | 1            |\n\n游戏缩写\n\n| 崩坏三 | 原神 | 崩坏二 | 未定事件簿 | 星穹铁道 | 大别野 | 绝区零 |\n| ------ | ---- | ------ | ---------- | -------- | ------ | ------ |\n| bh3    | ys   | bh2    | wd         | sr       | dby    | zzz    |\n\n主榜类型\n\n| 同人榜  | COS 榜 |\n| ------- | ------ |\n| tongren | cos    |\n\n子榜类型\n\n崩坏三 子榜\n\n| 插画         | 漫画  | COS |\n| ------------ | ----- | --- |\n| illustration | comic | cos |\n\n原神 子榜\n\n| 插画         | 漫画  | Q 版 | 手工   |\n| ------------ | ----- | ---- | ------ |\n| illustration | comic | qute | manual |\n\n排行榜类型\n\n| 日榜  | 周榜   | 月榜    |\n| ----- | ------ | ------- |\n| daily | weekly | monthly |",
  "example": "/mihoyo/bbs/img-ranking/ys/forumType=tongren&cateType=illustration&rankingType=daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 60,
  "location": "bbs/img-ranking.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "米游社 - 同人榜",
  "parameters": {
    "game": "游戏缩写",
    "routeParams": "额外参数；请参阅以下说明和表格"
  },
  "path": "/bbs/img-ranking/:game/:routeParams?",
  "radar": [
    {
      "source": [
        "miyoushe.com/:game/imgRanking/:forum_id/:ranking_id/:cate_id"
      ],
      "target": "/bbs/img-ranking/:game"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "米游社-原神-同人榜-插画榜-日榜 - Powered by RSSHub",
      "errorAt": "2025-12-24T13:26:51.180Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "41476070206969862",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs-api.miyoushe.com/post/wapi/getImagePostList?gids=2&forum_id=29&cate_id=4&type=1&page_size=20&last_id=",
      "title": "米游社-原神-同人榜-插画榜-日榜",
      "type": "feed",
      "url": "rsshub://mihoyo/bbs/img-ranking/ys/forumType=tongren&cateType=illustration&rankingType=daily"
    },
    {
      "description": "米游社-崩坏：星穹铁道-同人榜-日榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74617383214838784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs-api.miyoushe.com/post/wapi/getImagePostList?gids=6&forum_id=56&cate_id=0&type=1&page_size=20&last_id=",
      "title": "米游社-崩坏：星穹铁道-同人榜-日榜",
      "type": "feed",
      "url": "rsshub://mihoyo/bbs/img-ranking/sr/forumType=tongren&rankingType=daily"
    }
  ]
}
```
