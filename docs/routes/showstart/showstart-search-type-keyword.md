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
      "description": "秀动网 - 搜城市 - 成都 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "138149010608228352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/",
      "title": "秀动网 - 搜城市 - 成都",
      "type": "feed",
      "url": "rsshub://showstart/search/city/%20%E6%88%90%E9%83%BD"
    },
    {
      "description": "秀动网 - 搜城市 - 苏州 - Powered by RSSHub",
      "errorAt": "2026-08-01T15:08:24.781Z",
      "errorMessage": "e[t].localeCompare is not a function\n",
      "id": "175967172586634240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.showstart.com/",
      "title": "秀动网 - 搜城市 - 苏州",
      "type": "feed",
      "url": "rsshub://showstart/search/city/%E8%8B%8F%E5%B7%9E"
    }
  ]
}
```
