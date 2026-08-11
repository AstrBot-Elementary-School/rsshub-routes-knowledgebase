# AcFun - 文章

## Coverage
`index-only`

## Route
- Namespace: `acfun`
- Namespace Name: `AcFun`
- Route Path: `/acfun/article/:categoryId/:sortType?/:timeRange?`
- Route Name: `文章`
- Example: `/acfun/article/110`
- URL: `www.acfun.cn`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
| 二次元画师 | 综合 | 生活情感 | 游戏 | 动漫文化 | 漫画文学 |
| ---------- | ---- | -------- | ---- | -------- | -------- |
| 184        | 110  | 73       | 164  | 74       | 75       |

| 最新发表   | 最新动态        | 最热文章 |
| ---------- | --------------- | -------- |
| createTime | lastCommentTime | hotScore |

| 时间不限 | 24 小时 | 三天     | 一周    | 一个月   |
| -------- | ------- | -------- | ------- | -------- |
| all      | oneDay  | threeDay | oneWeek | oneMonth |

## Parameters
- `categoryId`: {"description": "分区 ID", "options": [{"label": "生活情感", "value": "73"}, {"label": "动漫文化", "value": "74"}, {"label": "漫画文学", "value": "75"}, {"label": "综合", "value": "110"}, {"label": "游戏", "value": "164"}, {"label": "二次元画师", "value": "184"}]}
- `sortType`: {"default": "createTime", "description": "排序", "options": [{"label": "最新发表", "value": "createTime"}, {"label": "最新动态", "value": "lastCommentTime"}, {"label": "最热文章", "value": "hotScore"}]}
- `timeRange`: {"default": "all", "description": "时间范围，仅在排序是 `hotScore` 有效", "options": [{"label": "时间不限", "value": "all"}, {"label": "24 小时", "value": "oneDay"}, {"label": "三天", "value": "threeDay"}, {"label": "一周", "value": "oneWeek"}, {"label": "一个月", "value": "oneMonth"}]}


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
    "anime"
  ],
  "description": "| 二次元画师 | 综合 | 生活情感 | 游戏 | 动漫文化 | 漫画文学 |\n| ---------- | ---- | -------- | ---- | -------- | -------- |\n| 184        | 110  | 73       | 164  | 74       | 75       |\n\n| 最新发表   | 最新动态        | 最热文章 |\n| ---------- | --------------- | -------- |\n| createTime | lastCommentTime | hotScore |\n\n| 时间不限 | 24 小时 | 三天     | 一周    | 一个月   |\n| -------- | ------- | -------- | ------- | -------- |\n| all      | oneDay  | threeDay | oneWeek | oneMonth |",
  "example": "/acfun/article/110",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1033,
  "location": "article.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "文章",
  "parameters": {
    "categoryId": {
      "description": "分区 ID",
      "options": [
        {
          "label": "生活情感",
          "value": "73"
        },
        {
          "label": "动漫文化",
          "value": "74"
        },
        {
          "label": "漫画文学",
          "value": "75"
        },
        {
          "label": "综合",
          "value": "110"
        },
        {
          "label": "游戏",
          "value": "164"
        },
        {
          "label": "二次元画师",
          "value": "184"
        }
      ]
    },
    "sortType": {
      "default": "createTime",
      "description": "排序",
      "options": [
        {
          "label": "最新发表",
          "value": "createTime"
        },
        {
          "label": "最新动态",
          "value": "lastCommentTime"
        },
        {
          "label": "最热文章",
          "value": "hotScore"
        }
      ]
    },
    "timeRange": {
      "default": "all",
      "description": "时间范围，仅在排序是 `hotScore` 有效",
      "options": [
        {
          "label": "时间不限",
          "value": "all"
        },
        {
          "label": "24 小时",
          "value": "oneDay"
        },
        {
          "label": "三天",
          "value": "threeDay"
        },
        {
          "label": "一周",
          "value": "oneWeek"
        },
        {
          "label": "一个月",
          "value": "oneMonth"
        }
      ]
    }
  },
  "path": "/article/:categoryId/:sortType?/:timeRange?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "综合 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72507406400191488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.acfun.cn/v/list110/index.htm",
      "title": "综合",
      "type": "feed",
      "url": "rsshub://acfun/article/110/createTime/all"
    },
    {
      "description": "动漫文化 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72507398900406272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.acfun.cn/v/list74/index.htm",
      "title": "动漫文化",
      "type": "feed",
      "url": "rsshub://acfun/article/74/createTime/all"
    }
  ],
  "view": 0
}
```
