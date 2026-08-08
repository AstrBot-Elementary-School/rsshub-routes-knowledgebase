# 网易公开课 - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/news/rank/:category?/:type?/:time?`
- Route Name: `排行榜`
- Example: `/163/news/rank/whole/click/day`
- URL: `163.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news/rank.ts`
- Source Module: `_None_`

## Description
::: tip
全站新闻 **点击榜** 的统计时间仅包含 “24 小时”、“本周”、“本月”，不包含 “1 小时”。即可用的`time`参数为`day`、`week`、`month`。

其他分类 **点击榜** 的统计时间仅包含 “1 小时”、“24 小时”、“本周”。即可用的`time`参数为`hour`、`day`、`week`。

而所有分类（包括全站）的 **跟贴榜** 的统计时间皆仅包含 “24 小时”、“本周”、“本月”。即可用的`time`参数为`day`、`week`、`month`。
:::

新闻分类：

| 全站  | 新闻 | 娱乐          | 体育   | 财经  | 科技 | 汽车 | 女人 | 房产  | 游戏 | 旅游   | 教育 |
| ----- | ---- | ------------- | ------ | ----- | ---- | ---- | ---- | ----- | ---- | ------ | ---- |
| whole | news | entertainment | sports | money | tech | auto | lady | house | game | travel | edu  |

## Parameters
- `category`: 新闻分类，参见下表，默认为“全站”
- `type`: 排行榜类型，“点击榜”对应`click`，“跟贴榜”对应`follow`，默认为“点击榜”
- `time`: 统计时间，“1小时”对应`hour`，“24小时”对应`day`，“本周”对应`week`，“本月”对应`month`，默认为“24小时”


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
    "new-media"
  ],
  "description": "::: tip\n全站新闻 **点击榜** 的统计时间仅包含 “24 小时”、“本周”、“本月”，不包含 “1 小时”。即可用的`time`参数为`day`、`week`、`month`。\n\n其他分类 **点击榜** 的统计时间仅包含 “1 小时”、“24 小时”、“本周”。即可用的`time`参数为`hour`、`day`、`week`。\n\n而所有分类（包括全站）的 **跟贴榜** 的统计时间皆仅包含 “24 小时”、“本周”、“本月”。即可用的`time`参数为`day`、`week`、`month`。\n:::\n\n新闻分类：\n\n| 全站  | 新闻 | 娱乐          | 体育   | 财经  | 科技 | 汽车 | 女人 | 房产  | 游戏 | 旅游   | 教育 |\n| ----- | ---- | ------------- | ------ | ----- | ---- | ---- | ---- | ----- | ---- | ------ | ---- |\n| whole | news | entertainment | sports | money | tech | auto | lady | house | game | travel | edu  |",
  "example": "/163/news/rank/whole/click/day",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "news/rank.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "排行榜",
  "parameters": {
    "category": "新闻分类，参见下表，默认为“全站”",
    "time": "统计时间，“1小时”对应`hour`，“24小时”对应`day`，“本周”对应`week`，“本月”对应`month`，默认为“24小时”",
    "type": "排行榜类型，“点击榜”对应`click`，“跟贴榜”对应`follow`，默认为“点击榜”"
  },
  "path": "/news/rank/:category?/:type?/:time?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "网易新闻24小时点击榜 - 全站 - Powered by RSSHub",
      "errorAt": "2026-05-08T11:48:10.437Z",
      "errorMessage": "Cannot create property 'description' on string '\"\"'\n",
      "id": "155624244600445952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.163.com/special/0001386F/rank_whole.html",
      "title": "网易新闻24小时点击榜 - 全站",
      "type": "feed",
      "url": "rsshub://163/news/rank"
    },
    {
      "description": "网易新闻24小时点击榜 - 全站 - Powered by RSSHub",
      "errorAt": "2026-07-03T07:41:31.858Z",
      "errorMessage": "Cannot create property 'description' on string '\"\"'\n",
      "id": "63981069772459008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.163.com/special/0001386F/rank_whole.html",
      "title": "网易新闻24小时点击榜 - 全站",
      "type": "feed",
      "url": "rsshub://163/news/rank/whole/click/day"
    }
  ]
}
```
