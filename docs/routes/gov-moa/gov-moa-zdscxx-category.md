# 中华人民共和国农业农村部 - 数据

## Coverage
`index-only`

## Route
- Namespace: `gov/moa`
- Namespace Name: `中华人民共和国农业农村部`
- Route Path: `/gov/moa/zdscxx/:category{.+}?`
- Route Name: `数据`
- Example: `/gov/moa/zdscxx`
- URL: `www.moa.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `zdscxx.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [中华人民共和国农业农村部数据](http://zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp) 的 `价格指数` 报告主题。此时路由为 [`/gov/moa/zdscxx/价格指数`](https://rsshub.app/gov/moa/zdscxx/价格指数)。

若订阅 `央视网` 报告来源 的 `蔬菜生产` 报告主题。此时路由为 [`/gov/moa/zdscxx/央视网/蔬菜生产`](https://rsshub.app/gov/moa/zdscxx/央视网/蔬菜生产)。
:::

| 价格指数 | 供需形势 | 分析报告周报 | 分析报告日报 | 日历信息 | 蔬菜生产 |
| -------- | -------- | ------------ | ------------ | -------- | -------- |

## Parameters
- `category`: 分类，默认为全部，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `价格指数`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/zdscxx/价格指数`
### Rule 2
- `title`: `供需形势`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/zdscxx/供需形势`
### Rule 3
- `title`: `分析报告周报`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/zdscxx/分析报告周报`
### Rule 4
- `title`: `分析报告日报`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/zdscxx/分析报告日报`
### Rule 5
- `title`: `日历信息`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/zdscxx/日历信息`
### Rule 6
- `title`: `蔬菜生产`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/zdscxx/蔬菜生产`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n若订阅 [中华人民共和国农业农村部数据](http://zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp) 的 `价格指数` 报告主题。此时路由为 [`/gov/moa/zdscxx/价格指数`](https://rsshub.app/gov/moa/zdscxx/价格指数)。\n\n若订阅 `央视网` 报告来源 的 `蔬菜生产` 报告主题。此时路由为 [`/gov/moa/zdscxx/央视网/蔬菜生产`](https://rsshub.app/gov/moa/zdscxx/央视网/蔬菜生产)。\n:::\n\n| 价格指数 | 供需形势 | 分析报告周报 | 分析报告日报 | 日历信息 | 蔬菜生产 |\n| -------- | -------- | ------------ | ------------ | -------- | -------- |",
  "example": "/gov/moa/zdscxx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 29,
  "location": "zdscxx.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "数据",
  "parameters": {
    "category": "分类，默认为全部，见下表"
  },
  "path": "/zdscxx/:category{.+}?",
  "radar": [
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/zdscxx/价格指数",
      "title": "价格指数"
    },
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/zdscxx/供需形势",
      "title": "供需形势"
    },
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/zdscxx/分析报告周报",
      "title": "分析报告周报"
    },
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/zdscxx/分析报告日报",
      "title": "分析报告日报"
    },
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/zdscxx/日历信息",
      "title": "日历信息"
    },
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/zdscxx/蔬菜生产",
      "title": "蔬菜生产"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "数据 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72147260240052224",
      "image": "https://www.moa.gov.cn/images/nyb_logo_V2018.png",
      "ownerUserId": null,
      "siteUrl": "http://zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp",
      "title": "中华人民共和国农业农村部",
      "type": "feed",
      "url": "rsshub://gov/moa/zdscxx"
    },
    {
      "description": "数据 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "92886505678071808",
      "image": "https://www.moa.gov.cn/images/nyb_logo_V2018.png",
      "ownerUserId": null,
      "siteUrl": "http://zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp",
      "title": "中华人民共和国农业农村部 - 价格指数",
      "type": "feed",
      "url": "rsshub://gov/moa/zdscxx/%E4%BB%B7%E6%A0%BC%E6%8C%87%E6%95%B0"
    }
  ],
  "url": "www.moa.gov.cn"
}
```
