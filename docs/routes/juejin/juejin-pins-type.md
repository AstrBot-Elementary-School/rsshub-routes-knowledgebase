# 掘金 - 沸点

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/juejin/pins/:type?`
- Route Name: `沸点`
- Example: `/juejin/pins/6824710202487472141`
- URL: `juejin.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `xyqfer, laampui`
- Source Location: `pins.ts`
- Source Module: `_None_`

## Description
| 推荐      | 热门 | 上班摸鱼            | 内推招聘            | 一图胜千言          | 今天学到了          | 每天一道算法题      | 开发工具推荐        | 树洞一下            |
| --------- | ---- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- |
| recommend | hot  | 6824710203301167112 | 6819970850532360206 | 6824710202487472141 | 6824710202562969614 | 6824710202378436621 | 6824710202000932877 | 6824710203112423437 |

## Parameters
- `type`: 默认为 recommend，见下表


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
    "programming"
  ],
  "description": "| 推荐      | 热门 | 上班摸鱼            | 内推招聘            | 一图胜千言          | 今天学到了          | 每天一道算法题      | 开发工具推荐        | 树洞一下            |\n| --------- | ---- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- |\n| recommend | hot  | 6824710203301167112 | 6819970850532360206 | 6824710202487472141 | 6824710202562969614 | 6824710202378436621 | 6824710202000932877 | 6824710203112423437 |",
  "example": "/juejin/pins/6824710202487472141",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 59,
  "location": "pins.ts",
  "maintainers": [
    "xyqfer",
    "laampui"
  ],
  "name": "沸点",
  "parameters": {
    "type": "默认为 recommend，见下表"
  },
  "path": "/pins/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "沸点 - 推荐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55215029121101840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/pins/recommended",
      "title": "沸点 - 推荐",
      "type": "feed",
      "url": "rsshub://juejin/pins"
    },
    {
      "description": "沸点 - 热门 - Powered by RSSHub",
      "errorAt": "2025-01-15T03:59:17.919Z",
      "errorMessage": "Cannot read properties of undefined (reading 'map')\n",
      "id": "61640871105037312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/pins/recommended",
      "title": "沸点 - 热门",
      "type": "feed",
      "url": "rsshub://juejin/pins/hot"
    }
  ]
}
```
