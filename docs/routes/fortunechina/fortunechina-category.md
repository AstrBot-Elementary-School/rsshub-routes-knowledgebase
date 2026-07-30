# 财富中文网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `fortunechina`
- Namespace Name: `财富中文网`
- Route Path: `/fortunechina/:category?`
- Route Name: `分类`
- Example: `/fortunechina`
- URL: `fortunechina.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 商业    | 领导力    | 科技 | 研究   |
| ------- | --------- | ---- | ------ |
| shangye | lindgaoli | keji | report |

## Parameters
- `category`: 分类，见下表，默认为首页


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
  - `fortunechina.com/:category`
  - `fortunechina.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 商业    | 领导力    | 科技 | 研究   |\n| ------- | --------- | ---- | ------ |\n| shangye | lindgaoli | keji | report |",
  "example": "/fortunechina",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 97,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为首页"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "fortunechina.com/:category",
        "fortunechina.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "财富中文网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42594297266876416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.fortunechina.com/",
      "title": "财富中文网",
      "type": "feed",
      "url": "rsshub://fortunechina"
    },
    {
      "description": "科技 - 财富中文网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42594177477129216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.fortunechina.com/keji",
      "title": "科技 - 财富中文网",
      "type": "feed",
      "url": "rsshub://fortunechina/keji"
    }
  ]
}
```
