# 秀动网 - 演出搜索

## Coverage
`index-only`

## Route
- Namespace: `showstart`
- Namespace Name: `秀动网`
- Route Path: `/showstart/search/:type/:keyword?`
- Route Name: `演出搜索`
- Example: `/showstart/search/live`
- URL: `www.showstart.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `lchtao26`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 搜索关键词
- `type`: {"description": "类别", "options": [{"label": "演出", "value": "event"}, {"label": "音乐人", "value": "artist"}, {"label": "场地", "value": "site"}, {"label": "厂牌", "value": "brand"}, {"label": "城市", "value": "city"}, {"label": "风格", "value": "style"}]}


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
  "example": "/showstart/search/live",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "search.ts",
  "maintainers": [
    "lchtao26"
  ],
  "name": "演出搜索",
  "parameters": {
    "keyword": "搜索关键词",
    "type": {
      "description": "类别",
      "options": [
        {
          "label": "演出",
          "value": "event"
        },
        {
          "label": "音乐人",
          "value": "artist"
        },
        {
          "label": "场地",
          "value": "site"
        },
        {
          "label": "厂牌",
          "value": "brand"
        },
        {
          "label": "城市",
          "value": "city"
        },
        {
          "label": "风格",
          "value": "style"
        }
      ]
    }
  },
  "path": "/search/:type/:keyword?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "秀动网 - 搜演出 - live - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72889425066383360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/",
      "title": "秀动网 - 搜演出 - live",
      "type": "feed",
      "url": "rsshub://showstart/search/live"
    },
    {
      "description": "秀动网 - 搜城市 - 上海 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67428435443757056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/",
      "title": "秀动网 - 搜城市 - 上海",
      "type": "feed",
      "url": "rsshub://showstart/search/city/%E4%B8%8A%E6%B5%B7"
    }
  ]
}
```
