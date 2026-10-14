# 网易公开课 - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/news/rank/:category/:type?/:time?`
- Route Name: `排行榜`
- Example: `/163/news/rank/money/click/day`
- URL: `163.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news/rank.ts`
- Source Module: `_None_`

## Description
::: tip
**点击榜** 的统计时间仅包含 “1 小时”、“24 小时”、“本周”。即可用的`time`参数为`hour`、`day`、`week`。

**跟贴榜** 的统计时间仅包含 “24 小时”、“本周”、“本月”。即可用的`time`参数为`day`、`week`、`month`。
:::

新闻分类：

| 新闻 | 娱乐          | 体育   | 财经  | 科技 | 汽车 | 女人 | 房产  | 游戏 | 旅游   | 教育 |
| ---- | ------------- | ------ | ----- | ---- | ---- | ---- | ----- | ---- | ------ | ---- |
| news | entertainment | sports | money | tech | auto | lady | house | game | travel | edu  |

## Parameters
- `category`: 新闻分类（必填），参见下表。旧全站排行榜已停止更新。
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
  "description": "::: tip\n**点击榜** 的统计时间仅包含 “1 小时”、“24 小时”、“本周”。即可用的`time`参数为`hour`、`day`、`week`。\n\n**跟贴榜** 的统计时间仅包含 “24 小时”、“本周”、“本月”。即可用的`time`参数为`day`、`week`、`month`。\n:::\n\n新闻分类：\n\n| 新闻 | 娱乐          | 体育   | 财经  | 科技 | 汽车 | 女人 | 房产  | 游戏 | 旅游   | 教育 |\n| ---- | ------------- | ------ | ----- | ---- | ---- | ---- | ----- | ---- | ------ | ---- |\n| news | entertainment | sports | money | tech | auto | lady | house | game | travel | edu  |",
  "example": "/163/news/rank/money/click/day",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news/rank.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "排行榜",
  "parameters": {
    "category": "新闻分类（必填），参见下表。旧全站排行榜已停止更新。",
    "time": "统计时间，“1小时”对应`hour`，“24小时”对应`day`，“本周”对应`week`，“本月”对应`month`，默认为“24小时”",
    "type": "排行榜类型，“点击榜”对应`click`，“跟贴榜”对应`follow`，默认为“点击榜”"
  },
  "path": "/news/rank/:category/:type?/:time?",
  "topFeeds": []
}
```
