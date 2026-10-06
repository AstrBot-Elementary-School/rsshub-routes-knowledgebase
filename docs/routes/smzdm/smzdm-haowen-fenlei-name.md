# 什么值得买 - 好文分类

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/smzdm/haowen/fenlei/:name`
- Route Name: `好文分类`
- Example: `/smzdm/haowen/fenlei/shenghuodianqi`
- URL: `post.smzdm.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `LogicJake`
- Source Location: `haowen-fenlei.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 分类名，可在 URL 中查看


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.smzdm.com/fenlei/:name`
- `target`: `/haowen/fenlei/:name`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/smzdm/haowen/fenlei/shenghuodianqi",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "haowen-fenlei.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "好文分类",
  "parameters": {
    "name": "分类名，可在 URL 中查看"
  },
  "path": "/haowen/fenlei/:name",
  "radar": [
    {
      "source": [
        "www.smzdm.com/fenlei/:name"
      ],
      "target": "/haowen/fenlei/:name"
    }
  ],
  "topFeeds": []
}
```
