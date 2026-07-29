# 温州大学 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `wzu`
- Namespace Name: `温州大学`
- Route Path: `/wzu/news/:type?`
- Route Name: `新闻`
- Example: `/wzu/news/0`
- URL: `wzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Chandler-Lu`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 温大新闻 | 媒体温大 | 学术温大 | 通知公告 | 招标信息 | 学术公告 |
| :------: | :------: | :------: | :------: | :------: | :------: |
|     0    |     1    |     2    |     3    |     4    |     5    |

## Parameters
- `type`: 分类，见下表 默认为`0`


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 温大新闻 | 媒体温大 | 学术温大 | 通知公告 | 招标信息 | 学术公告 |\n| :------: | :------: | :------: | :------: | :------: | :------: |\n|     0    |     1    |     2    |     3    |     4    |     5    |",
  "example": "/wzu/news/0",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "Chandler-Lu"
  ],
  "name": "新闻",
  "parameters": {
    "type": "分类，见下表 默认为`0`"
  },
  "path": "/news/:type?",
  "topFeeds": []
}
```
