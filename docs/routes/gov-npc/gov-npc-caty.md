# 全国人民代表大会 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/npc`
- Namespace Name: `全国人民代表大会`
- Route Path: `/gov/npc/:caty`
- Route Name: `通用`
- Example: `/gov/npc/c183`
- URL: `www.npc.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `233yeee`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 立法 | 监督 | 代表 | 理论 | 权威发布 | 滚动新闻 |
| ---- | ---- | ---- | ---- | -------- | -------- |
| c183 | c184 | c185 | c189 | c12435   | c10134   |

## Parameters
- `caty`: 分类名，支持形如 `http://www.npc.gov.cn/npc/c2/*/` 的网站，传入 npc 之后的参数


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `npc.gov.cn/npc/c2/:caty`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 立法 | 监督 | 代表 | 理论 | 权威发布 | 滚动新闻 |\n| ---- | ---- | ---- | ---- | -------- | -------- |\n| c183 | c184 | c185 | c189 | c12435   | c10134   |",
  "example": "/gov/npc/c183",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1111,
  "location": "index.ts",
  "maintainers": [
    "233yeee"
  ],
  "name": "通用",
  "parameters": {
    "caty": "分类名，支持形如 `http://www.npc.gov.cn/npc/c2/*/` 的网站，传入 npc 之后的参数"
  },
  "path": "/:caty",
  "radar": [
    {
      "source": [
        "npc.gov.cn/npc/c2/:caty"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "权威发布_中国人大网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76238928708564992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.npc.gov.cn/npc/c2/c12435/",
      "title": "权威发布_中国人大网",
      "type": "feed",
      "url": "rsshub://gov/npc/c12435"
    },
    {
      "description": "立法_中国人大网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62717033472135175",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.npc.gov.cn/npc/c2/c183/",
      "title": "立法_中国人大网",
      "type": "feed",
      "url": "rsshub://gov/npc/c183"
    }
  ]
}
```
