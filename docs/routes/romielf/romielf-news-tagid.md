# 每日赛车 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `romielf`
- Namespace Name: `每日赛车`
- Route Path: `/romielf/news/:tagId?`
- Route Name: `新闻`
- Example: `/romielf/news`
- URL: `www.romielf.com`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tagId`: {"default": "1", "description": "导航标签 id，可在 `https://api.romielf.com/index/navitv2` 查看", "options": [{"label": "头条", "value": "1"}, {"label": "科普", "value": "3"}, {"label": "MotoGP", "value": "5"}, {"label": "专栏", "value": "18"}, {"label": "视频", "value": "19"}, {"label": "FE", "value": "52"}, {"label": "达喀尔", "value": "57"}, {"label": "新车发布", "value": "64"}, {"label": "TCR", "value": "125"}, {"label": "纽维自传", "value": "126"}, {"label": "TopSpeed最速档", "value": "127"}, {"label": "赛会信息", "value": "156"}, {"label": "社交媒体", "value": "158"}, {"label": "FIA文档", "value": "159"}, {"label": "F1运动规则", "value": "175"}, {"label": "新闻媒体", "value": "223"}]}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/romielf/news",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "新闻",
  "parameters": {
    "tagId": {
      "default": "1",
      "description": "导航标签 id，可在 `https://api.romielf.com/index/navitv2` 查看",
      "options": [
        {
          "label": "头条",
          "value": "1"
        },
        {
          "label": "科普",
          "value": "3"
        },
        {
          "label": "MotoGP",
          "value": "5"
        },
        {
          "label": "专栏",
          "value": "18"
        },
        {
          "label": "视频",
          "value": "19"
        },
        {
          "label": "FE",
          "value": "52"
        },
        {
          "label": "达喀尔",
          "value": "57"
        },
        {
          "label": "新车发布",
          "value": "64"
        },
        {
          "label": "TCR",
          "value": "125"
        },
        {
          "label": "纽维自传",
          "value": "126"
        },
        {
          "label": "TopSpeed最速档",
          "value": "127"
        },
        {
          "label": "赛会信息",
          "value": "156"
        },
        {
          "label": "社交媒体",
          "value": "158"
        },
        {
          "label": "FIA文档",
          "value": "159"
        },
        {
          "label": "F1运动规则",
          "value": "175"
        },
        {
          "label": "新闻媒体",
          "value": "223"
        }
      ]
    }
  },
  "path": "/news/:tagId?",
  "topFeeds": [],
  "url": "www.romielf.com"
}
```
