# 优设网 - 行业新闻

## Coverage
`index-only`

## Route
- Namespace: `uisdc`
- Namespace Name: `优设网`
- Route Path: `/uisdc/hangye/:caty?`
- Route Name: `行业新闻`
- Example: `/uisdc/hangye`
- URL: `www.uisdc.com`
- Language: `_None_`
- Categories: `design`
- Maintainers: `nczitzk`
- Source Location: `hangye.ts`
- Source Module: `_None_`

## Description
| 全部新闻 | 活动赛事        | 品牌资讯   | 新品推荐     |
| -------- | --------------- | ---------- | ------------ |
|          | events-activity | brand-news | new-products |

## Parameters
- `caty`: 分类，见下表，默认为全部新闻


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "description": "| 全部新闻 | 活动赛事        | 品牌资讯   | 新品推荐     |\n| -------- | --------------- | ---------- | ------------ |\n|          | events-activity | brand-news | new-products |",
  "example": "/uisdc/hangye",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "hangye.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "行业新闻",
  "parameters": {
    "caty": "分类，见下表，默认为全部新闻"
  },
  "path": "/hangye/:caty?",
  "topFeeds": []
}
```
