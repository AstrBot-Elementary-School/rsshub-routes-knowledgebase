# 虎嗅 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `huxiu`
- Namespace Name: `虎嗅`
- Route Path: `/huxiu/search/:keyword`
- Route Name: `搜索`
- Example: `/huxiu/search/生活`
- URL: `huxiu.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `xyqfer, HenryQW, nczitzk`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键字


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `huxiu.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/huxiu/search/生活",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 40,
  "location": "search.ts",
  "maintainers": [
    "xyqfer",
    "HenryQW",
    "nczitzk"
  ],
  "name": "搜索",
  "parameters": {
    "keyword": "关键字"
  },
  "path": "/search/:keyword",
  "radar": [
    {
      "source": [
        "huxiu.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "虎嗅 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66332234198832151",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.huxiu.com/",
      "title": "虎嗅搜索-搜索结果-虎嗅早报",
      "type": "feed",
      "url": "rsshub://huxiu/search/%E8%99%8E%E5%97%85%E6%97%A9%E6%8A%A5"
    },
    {
      "description": "虎嗅 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84597162601054208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.huxiu.com/",
      "title": "虎嗅搜索-搜索结果-智能体",
      "type": "feed",
      "url": "rsshub://huxiu/search/%E6%99%BA%E8%83%BD%E4%BD%93"
    }
  ],
  "url": "huxiu.com/"
}
```
