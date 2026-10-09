# 雪球 - 组合最新调仓信息

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/snb/:id`
- Route Name: `组合最新调仓信息`
- Example: `/xueqiu/snb/ZH1288184`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `ZhishanZhang`
- Source Location: `snb.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 组合代码, 可在组合主页 URL 中找到.


## Features
- `requireConfig`: [{"description": "需要登录才能访问的组合请配置雪球登录 Cookie。", "name": "XUEQIU_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xueqiu.com/P/:id`
  - `xueqiu.com/p/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/xueqiu/snb/ZH1288184",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "需要登录才能访问的组合请配置雪球登录 Cookie。",
        "name": "XUEQIU_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "snb.ts",
  "maintainers": [
    "ZhishanZhang"
  ],
  "name": "组合最新调仓信息",
  "parameters": {
    "id": "组合代码, 可在组合主页 URL 中找到."
  },
  "path": "/snb/:id",
  "radar": [
    {
      "source": [
        "xueqiu.com/P/:id",
        "xueqiu.com/p/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
