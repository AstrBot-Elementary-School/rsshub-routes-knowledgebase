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
| lastId      | 首屏游标                              | 省略或 0                                                             | 空           |

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
  - `miyoushe.com/bh2/imgRanking/40/2/:cateId`
- `target`: `/bbs/img-ranking/bh2/forumType=tongren&rankingType=weekly`
### Rule 2
- `source`:
  - `miyoushe.com/bh2/imgRanking/40/3/:cateId`
- `target`: `/bbs/img-ranking/bh2/forumType=tongren&rankingType=monthly`
### Rule 3
- `source`:
  - `miyoushe.com/bh3/imgRanking/4/1/3`
- `target`: `/bbs/img-ranking/bh3/forumType=tongren&rankingType=daily&cateType=comic`
### Rule 4
- `source`:
  - `miyoushe.com/bh3/imgRanking/4/1/4`
- `target`: `/bbs/img-ranking/bh3/forumType=tongren&rankingType=daily&cateType=illustration`
### Rule 5
- `source`:
  - `miyoushe.com/bh3/imgRanking/4/1/17`
- `target`: `/bbs/img-ranking/bh3/forumType=tongren&rankingType=daily&cateType=cos`
### Rule 6
- `source`:
  - `miyoushe.com/bh3/imgRanking/4/2/3`
- `target`: `/bbs/img-ranking/bh3/forumType=tongren&rankingType=weekly&cateType=comic`
### Rule 7
- `source`:
  - `miyoushe.com/bh3/imgRanking/4/2/4`
- `target`: `/bbs/img-ranking/bh3/forumType=tongren&rankingType=weekly&cateType=illustration`
### Rule 8
- `source`:
  - `miyoushe.com/bh3/imgRanking/4/2/17`
- `target`: `/bbs/img-ranking/bh3/forumType=tongren&rankingType=weekly&cateType=cos`
### Rule 9
- `source`:
  - `miyoushe.com/bh3/imgRanking/4/3/3`
- `target`: `/bbs/img-ranking/bh3/forumType=tongren&rankingType=monthly&cateType=comic`
### Rule 10
- `source`:
  - `miyoushe.com/bh3/imgRanking/4/3/4`
- `target`: `/bbs/img-ranking/bh3/forumType=tongren&rankingType=monthly&cateType=illustration`
### Rule 11
- `source`:
  - `miyoushe.com/bh3/imgRanking/4/3/17`
- `target`: `/bbs/img-ranking/bh3/forumType=tongren&rankingType=monthly&cateType=cos`
### Rule 12
- `source`:
  - `miyoushe.com/ys/imgRanking/29/1/1`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=daily&cateType=manual`
### Rule 13
- `source`:
  - `miyoushe.com/ys/imgRanking/29/1/2`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=daily&cateType=qute`
### Rule 14
- `source`:
  - `miyoushe.com/ys/imgRanking/29/1/3`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=daily&cateType=comic`
### Rule 15
- `source`:
  - `miyoushe.com/ys/imgRanking/29/1/4`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=daily&cateType=illustration`
### Rule 16
- `source`:
  - `miyoushe.com/ys/imgRanking/29/2/1`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=weekly&cateType=manual`
### Rule 17
- `source`:
  - `miyoushe.com/ys/imgRanking/29/2/2`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=weekly&cateType=qute`
### Rule 18
- `source`:
  - `miyoushe.com/ys/imgRanking/29/2/3`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=weekly&cateType=comic`
### Rule 19
- `source`:
  - `miyoushe.com/ys/imgRanking/29/2/4`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=weekly&cateType=illustration`
### Rule 20
- `source`:
  - `miyoushe.com/ys/imgRanking/29/3/1`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=monthly&cateType=manual`
### Rule 21
- `source`:
  - `miyoushe.com/ys/imgRanking/29/3/2`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=monthly&cateType=qute`
### Rule 22
- `source`:
  - `miyoushe.com/ys/imgRanking/29/3/3`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=monthly&cateType=comic`
### Rule 23
- `source`:
  - `miyoushe.com/ys/imgRanking/29/3/4`
- `target`: `/bbs/img-ranking/ys/forumType=tongren&rankingType=monthly&cateType=illustration`
### Rule 24
- `source`:
  - `miyoushe.com/ys/imgRanking/49/1/:cateId`
- `target`: `/bbs/img-ranking/ys/forumType=cos&rankingType=daily`
### Rule 25
- `source`:
  - `miyoushe.com/ys/imgRanking/49/2/:cateId`
- `target`: `/bbs/img-ranking/ys/forumType=cos&rankingType=weekly`
### Rule 26
- `source`:
  - `miyoushe.com/ys/imgRanking/49/3/:cateId`
- `target`: `/bbs/img-ranking/ys/forumType=cos&rankingType=monthly`
### Rule 27
- `source`:
  - `miyoushe.com/wd/imgRanking/38/1/:cateId`
- `target`: `/bbs/img-ranking/wd/forumType=tongren&rankingType=daily`
### Rule 28
- `source`:
  - `miyoushe.com/wd/imgRanking/38/2/:cateId`
- `target`: `/bbs/img-ranking/wd/forumType=tongren&rankingType=weekly`
### Rule 29
- `source`:
  - `miyoushe.com/wd/imgRanking/38/3/:cateId`
- `target`: `/bbs/img-ranking/wd/forumType=tongren&rankingType=monthly`
### Rule 30
- `source`:
  - `miyoushe.com/sr/imgRanking/56/1/:cateId`
- `target`: `/bbs/img-ranking/sr/forumType=tongren&rankingType=daily`
### Rule 31
- `source`:
  - `miyoushe.com/sr/imgRanking/56/2/:cateId`
- `target`: `/bbs/img-ranking/sr/forumType=tongren&rankingType=weekly`
### Rule 32
- `source`:
  - `miyoushe.com/sr/imgRanking/56/3/:cateId`
- `target`: `/bbs/img-ranking/sr/forumType=tongren&rankingType=monthly`
### Rule 33
- `source`:
  - `miyoushe.com/zzz/imgRanking/59/1/:cateId`
- `target`: `/bbs/img-ranking/zzz/forumType=tongren&rankingType=daily`
### Rule 34
- `source`:
  - `miyoushe.com/zzz/imgRanking/59/2/:cateId`
- `target`: `/bbs/img-ranking/zzz/forumType=tongren&rankingType=weekly`
### Rule 35
- `source`:
  - `miyoushe.com/zzz/imgRanking/59/3/:cateId`
- `target`: `/bbs/img-ranking/zzz/forumType=tongren&rankingType=monthly`
### Rule 36
- `source`:
  - `miyoushe.com/dby/imgRanking/39/1/:cateId`
- `target`: `/bbs/img-ranking/dby/forumType=tongren&rankingType=daily`
### Rule 37
- `source`:
  - `miyoushe.com/dby/imgRanking/39/2/:cateId`
- `target`: `/bbs/img-ranking/dby/forumType=tongren&rankingType=weekly`
### Rule 38
- `source`:
  - `miyoushe.com/dby/imgRanking/39/3/:cateId`
- `target`: `/bbs/img-ranking/dby/forumType=tongren&rankingType=monthly`
### Rule 39
- `source`:
  - `miyoushe.com/dby/imgRanking/47/1/:cateId`
- `target`: `/bbs/img-ranking/dby/forumType=cos&rankingType=daily`
### Rule 40
- `source`:
  - `miyoushe.com/dby/imgRanking/47/2/:cateId`
- `target`: `/bbs/img-ranking/dby/forumType=cos&rankingType=weekly`
### Rule 41
- `source`:
  - `miyoushe.com/dby/imgRanking/47/3/:cateId`
- `target`: `/bbs/img-ranking/dby/forumType=cos&rankingType=monthly`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 键          | 含义                                  | 接受的值                                                             | 默认值       |\n| ----------- | ------------------------------------- | -------------------------------------------------------------------- | ------------ |\n| forumType   | 主榜类型（仅原神、大别野有 cos 主榜） | tongren/cos                                                          | tongren      |\n| cateType    | 子榜类型（仅崩坏三、原神有子榜）      | 崩坏三：illustration/comic/cos；原神：illustration/comic/qute/manual | illustration |\n| rankingType | 排行榜类型（崩坏二没有日榜）          | daily/weekly/monthly                                                 | daily        |\n| lastId      | 首屏游标                              | 省略或 0                                                             | 空           |\n\n游戏缩写\n\n| 崩坏三 | 原神 | 崩坏二 | 未定事件簿 | 星穹铁道 | 大别野 | 绝区零 |\n| ------ | ---- | ------ | ---------- | -------- | ------ | ------ |\n| bh3    | ys   | bh2    | wd         | sr       | dby    | zzz    |\n\n主榜类型\n\n| 同人榜  | COS 榜 |\n| ------- | ------ |\n| tongren | cos    |\n\n子榜类型\n\n崩坏三 子榜\n\n| 插画         | 漫画  | COS |\n| ------------ | ----- | --- |\n| illustration | comic | cos |\n\n原神 子榜\n\n| 插画         | 漫画  | Q 版 | 手工   |\n| ------------ | ----- | ---- | ------ |\n| illustration | comic | qute | manual |\n\n排行榜类型\n\n| 日榜  | 周榜   | 月榜    |\n| ----- | ------ | ------- |\n| daily | weekly | monthly |",
  "example": "/mihoyo/bbs/img-ranking/ys/forumType=tongren&cateType=illustration&rankingType=daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 59,
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
        "miyoushe.com/bh2/imgRanking/40/2/:cateId"
      ],
      "target": "/bbs/img-ranking/bh2/forumType=tongren&rankingType=weekly"
    },
    {
      "source": [
        "miyoushe.com/bh2/imgRanking/40/3/:cateId"
      ],
      "target": "/bbs/img-ranking/bh2/forumType=tongren&rankingType=monthly"
    },
    {
      "source": [
        "miyoushe.com/bh3/imgRanking/4/1/3"
      ],
      "target": "/bbs/img-ranking/bh3/forumType=tongren&rankingType=daily&cateType=comic"
    },
    {
      "source": [
        "miyoushe.com/bh3/imgRanking/4/1/4"
      ],
      "target": "/bbs/img-ranking/bh3/forumType=tongren&rankingType=daily&cateType=illustration"
    },
    {
      "source": [
        "miyoushe.com/bh3/imgRanking/4/1/17"
      ],
      "target": "/bbs/img-ranking/bh3/forumType=tongren&rankingType=daily&cateType=cos"
    },
    {
      "source": [
        "miyoushe.com/bh3/imgRanking/4/2/3"
      ],
      "target": "/bbs/img-ranking/bh3/forumType=tongren&rankingType=weekly&cateType=comic"
    },
    {
      "source": [
        "miyoushe.com/bh3/imgRanking/4/2/4"
      ],
      "target": "/bbs/img-ranking/bh3/forumType=tongren&rankingType=weekly&cateType=illustration"
    },
    {
      "source": [
        "miyoushe.com/bh3/imgRanking/4/2/17"
      ],
      "target": "/bbs/img-ranking/bh3/forumType=tongren&rankingType=weekly&cateType=cos"
    },
    {
      "source": [
        "miyoushe.com/bh3/imgRanking/4/3/3"
      ],
      "target": "/bbs/img-ranking/bh3/forumType=tongren&rankingType=monthly&cateType=comic"
    },
    {
      "source": [
        "miyoushe.com/bh3/imgRanking/4/3/4"
      ],
      "target": "/bbs/img-ranking/bh3/forumType=tongren&rankingType=monthly&cateType=illustration"
    },
    {
      "source": [
        "miyoushe.com/bh3/imgRanking/4/3/17"
      ],
      "target": "/bbs/img-ranking/bh3/forumType=tongren&rankingType=monthly&cateType=cos"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/1/1"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=daily&cateType=manual"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/1/2"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=daily&cateType=qute"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/1/3"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=daily&cateType=comic"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/1/4"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=daily&cateType=illustration"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/2/1"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=weekly&cateType=manual"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/2/2"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=weekly&cateType=qute"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/2/3"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=weekly&cateType=comic"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/2/4"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=weekly&cateType=illustration"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/3/1"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=monthly&cateType=manual"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/3/2"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=monthly&cateType=qute"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/3/3"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=monthly&cateType=comic"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/29/3/4"
      ],
      "target": "/bbs/img-ranking/ys/forumType=tongren&rankingType=monthly&cateType=illustration"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/49/1/:cateId"
      ],
      "target": "/bbs/img-ranking/ys/forumType=cos&rankingType=daily"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/49/2/:cateId"
      ],
      "target": "/bbs/img-ranking/ys/forumType=cos&rankingType=weekly"
    },
    {
      "source": [
        "miyoushe.com/ys/imgRanking/49/3/:cateId"
      ],
      "target": "/bbs/img-ranking/ys/forumType=cos&rankingType=monthly"
    },
    {
      "source": [
        "miyoushe.com/wd/imgRanking/38/1/:cateId"
      ],
      "target": "/bbs/img-ranking/wd/forumType=tongren&rankingType=daily"
    },
    {
      "source": [
        "miyoushe.com/wd/imgRanking/38/2/:cateId"
      ],
      "target": "/bbs/img-ranking/wd/forumType=tongren&rankingType=weekly"
    },
    {
      "source": [
        "miyoushe.com/wd/imgRanking/38/3/:cateId"
      ],
      "target": "/bbs/img-ranking/wd/forumType=tongren&rankingType=monthly"
    },
    {
      "source": [
        "miyoushe.com/sr/imgRanking/56/1/:cateId"
      ],
      "target": "/bbs/img-ranking/sr/forumType=tongren&rankingType=daily"
    },
    {
      "source": [
        "miyoushe.com/sr/imgRanking/56/2/:cateId"
      ],
      "target": "/bbs/img-ranking/sr/forumType=tongren&rankingType=weekly"
    },
    {
      "source": [
        "miyoushe.com/sr/imgRanking/56/3/:cateId"
      ],
      "target": "/bbs/img-ranking/sr/forumType=tongren&rankingType=monthly"
    },
    {
      "source": [
        "miyoushe.com/zzz/imgRanking/59/1/:cateId"
      ],
      "target": "/bbs/img-ranking/zzz/forumType=tongren&rankingType=daily"
    },
    {
      "source": [
        "miyoushe.com/zzz/imgRanking/59/2/:cateId"
      ],
      "target": "/bbs/img-ranking/zzz/forumType=tongren&rankingType=weekly"
    },
    {
      "source": [
        "miyoushe.com/zzz/imgRanking/59/3/:cateId"
      ],
      "target": "/bbs/img-ranking/zzz/forumType=tongren&rankingType=monthly"
    },
    {
      "source": [
        "miyoushe.com/dby/imgRanking/39/1/:cateId"
      ],
      "target": "/bbs/img-ranking/dby/forumType=tongren&rankingType=daily"
    },
    {
      "source": [
        "miyoushe.com/dby/imgRanking/39/2/:cateId"
      ],
      "target": "/bbs/img-ranking/dby/forumType=tongren&rankingType=weekly"
    },
    {
      "source": [
        "miyoushe.com/dby/imgRanking/39/3/:cateId"
      ],
      "target": "/bbs/img-ranking/dby/forumType=tongren&rankingType=monthly"
    },
    {
      "source": [
        "miyoushe.com/dby/imgRanking/47/1/:cateId"
      ],
      "target": "/bbs/img-ranking/dby/forumType=cos&rankingType=daily"
    },
    {
      "source": [
        "miyoushe.com/dby/imgRanking/47/2/:cateId"
      ],
      "target": "/bbs/img-ranking/dby/forumType=cos&rankingType=weekly"
    },
    {
      "source": [
        "miyoushe.com/dby/imgRanking/47/3/:cateId"
      ],
      "target": "/bbs/img-ranking/dby/forumType=cos&rankingType=monthly"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "米游社-原神-同人榜-插画榜-日榜 - Powered by RSSHub",
      "errorAt": "2025-12-24T13:26:51.180Z",
      "errorMessage": "Failed to fetch\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
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
      "errorAt": "2026-10-13T22:36:45.262Z",
      "errorMessage": "503 \n",
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
