# 雪球 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/user/:id/:type?`
- Route Name: `用户动态`
- Example: `/xueqiu/user/8152922548`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `imlonghao`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
| 原发布 | 长文 | 问答 | 热门 | 交易 |
| ------ | ---- | ---- | ---- | ---- |
| 0      | 2    | 4    | 9    | 11   |

## Parameters
- `id`: 用户 id, 可在用户主页 URL 中找到
- `type`: 动态的类型, 不填则默认全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xueqiu.com/u/:id`
- `target`: `/user/:id`

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "description": "| 原发布 | 长文 | 问答 | 热门 | 交易 |\n| ------ | ---- | ---- | ---- | ---- |\n| 0      | 2    | 4    | 9    | 11   |",
  "example": "/xueqiu/user/8152922548",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2881,
  "location": "user.ts",
  "maintainers": [
    "imlonghao"
  ],
  "name": "用户动态",
  "parameters": {
    "id": "用户 id, 可在用户主页 URL 中找到",
    "type": "动态的类型, 不填则默认全部"
  },
  "path": "/user/:id/:type?",
  "radar": [
    {
      "source": [
        "xueqiu.com/u/:id"
      ],
      "target": "/user/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "大道无形我有型 的雪球全部动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54945423974379543",
      "image": "https://xavatar.imedao.com/community/20263/1777391133564-1777391133895.jpg!180x180.png",
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/u/1247347556",
      "title": "大道无形我有型 的雪球全部动态",
      "type": "feed",
      "url": "rsshub://xueqiu/user/1247347556"
    },
    {
      "description": "超级鹿鼎公 的雪球全部动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60231927983439872",
      "image": "https://xavatar.imedao.com/community/20147/1408271545017-1408271562251.jpg!180x180.png",
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/u/8790885129",
      "title": "超级鹿鼎公 的雪球全部动态",
      "type": "feed",
      "url": "rsshub://xueqiu/user/8790885129"
    }
  ]
}
```
