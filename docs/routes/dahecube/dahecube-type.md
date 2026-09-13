# 大河财立方 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `dahecube`
- Namespace Name: `大河财立方`
- Route Path: `/dahecube/:type?`
- Route Name: `新闻`
- Example: `/dahecube`
- URL: `dahecube.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `linbuxiao`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 推荐      | 党史    | 豫股  | 财经     | 投教      | 金融    | 科创    | 投融   | 专栏   |
| --------- | ------- | ----- | -------- | --------- | ------- | ------- | ------ | ------ |
| recommend | history | stock | business | education | finance | science | invest | column |

## Parameters
- `type`: 板块，见下表，默认为推荐


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
  "description": "| 推荐      | 党史    | 豫股  | 财经     | 投教      | 金融    | 科创    | 投融   | 专栏   |\n| --------- | ------- | ----- | -------- | --------- | ------- | ------- | ------ | ------ |\n| recommend | history | stock | business | education | finance | science | invest | column |",
  "example": "/dahecube",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "index.ts",
  "maintainers": [
    "linbuxiao"
  ],
  "name": "新闻",
  "parameters": {
    "type": "板块，见下表，默认为推荐"
  },
  "path": "/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "大河财立方 推荐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73611588824278016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dahecube.com/index.html?recid=1",
      "title": "大河财立方",
      "type": "feed",
      "url": "rsshub://dahecube"
    },
    {
      "description": "大河财立方 推荐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79864002134590464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dahecube.com/index.html?recid=1",
      "title": "大河财立方",
      "type": "feed",
      "url": "rsshub://dahecube/recommend"
    }
  ]
}
```
