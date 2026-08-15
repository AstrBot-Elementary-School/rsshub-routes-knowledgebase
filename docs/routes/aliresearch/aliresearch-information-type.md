# 阿里研究院 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `aliresearch`
- Namespace Name: `阿里研究院`
- Route Path: `/aliresearch/information/:type?`
- Route Name: `资讯`
- Example: `/aliresearch/information`
- URL: `aliresearch.com/cn/information`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `information.ts`
- Source Module: `_None_`

## Description
| 新闻 | 观点 | 案例 |
| ---- | ---- | ---- |

## Parameters
- `type`: 类型，见下表，默认为新闻


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
  - `aliresearch.com/cn/information`
  - `aliresearch.com/`
- `target`: `/information`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 新闻 | 观点 | 案例 |\n| ---- | ---- | ---- |",
  "example": "/aliresearch/information",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1135,
  "location": "information.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "type": "类型，见下表，默认为新闻"
  },
  "path": "/information/:type?",
  "radar": [
    {
      "source": [
        "aliresearch.com/cn/information",
        "aliresearch.com/"
      ],
      "target": "/information"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "阿里研究院 - 新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42593963123453952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.aliresearch.com/cn/information",
      "title": "阿里研究院 - 新闻",
      "type": "feed",
      "url": "rsshub://aliresearch/information"
    },
    {
      "description": "阿里研究院 - 新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84270409115778048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.aliresearch.com/cn/information",
      "title": "阿里研究院 - 新闻",
      "type": "feed",
      "url": "rsshub://aliresearch/information/%E6%96%B0%E9%97%BB"
    }
  ],
  "url": "aliresearch.com/cn/information"
}
```
