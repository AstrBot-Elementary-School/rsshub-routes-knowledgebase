# 淘宝网 - 众筹项目

## Coverage
`index-only`

## Route
- Namespace: `taobao`
- Namespace Name: `淘宝网`
- Route Path: `/taobao/zhongchou/:type?`
- Route Name: `众筹项目`
- Example: `/taobao/zhongchou/all`
- URL: `taobao.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `xyqfer, Fatpandac`
- Source Location: `zhongchou.tsx`
- Source Module: `_None_`

## Description
| 全部 | 科技 | 食品        | 动漫 | 设计   | 公益 | 娱乐 | 影音  | 书籍 | 游戏 | 其他  |
| ---- | ---- | ----------- | ---- | ------ | ---- | ---- | ----- | ---- | ---- | ----- |
| all  | tech | agriculture | acg  | design | love | tele | music | book | game | other |

## Parameters
- `type`: 类型, 默认为 `all` 全部


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
    "shopping"
  ],
  "description": "| 全部 | 科技 | 食品        | 动漫 | 设计   | 公益 | 娱乐 | 影音  | 书籍 | 游戏 | 其他  |\n| ---- | ---- | ----------- | ---- | ------ | ---- | ---- | ----- | ---- | ---- | ----- |\n| all  | tech | agriculture | acg  | design | love | tele | music | book | game | other |",
  "example": "/taobao/zhongchou/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 94,
  "location": "zhongchou.tsx",
  "maintainers": [
    "xyqfer",
    "Fatpandac"
  ],
  "name": "众筹项目",
  "parameters": {
    "type": "类型, 默认为 `all` 全部"
  },
  "path": "/zhongchou/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "淘宝众筹-all - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61055526802873344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://izhongchou.taobao.com/index.htm",
      "title": "淘宝众筹-all",
      "type": "feed",
      "url": "rsshub://taobao/zhongchou/all"
    },
    {
      "description": "淘宝众筹-all - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "111128431392705536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://izhongchou.taobao.com/index.htm",
      "title": "淘宝众筹-all",
      "type": "feed",
      "url": "rsshub://taobao/zhongchou"
    }
  ]
}
```
