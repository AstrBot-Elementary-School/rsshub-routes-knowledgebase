# iThome 台灣 - 标签

## Coverage
`index-only`

## Route
- Namespace: `ithome`
- Namespace Name: `iThome 台灣`
- Route Path: `/ithome/tag/:name`
- Route Name: `标签`
- Example: `/ithome/tag/win11`
- URL: `ithome.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 标签名称，可从网址链接中获取


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
  - `ithome.com/tag/:name`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ithome/tag/win11",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 29,
  "location": "tag.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "标签",
  "parameters": {
    "name": "标签名称，可从网址链接中获取"
  },
  "path": "/tag/:name",
  "radar": [
    {
      "source": [
        "ithome.com/tag/:name"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "IT之家 - ai标签 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "127730216447523840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ithome.com/tag/ai",
      "title": "IT之家 - ai标签",
      "type": "feed",
      "url": "rsshub://ithome/tag/ai"
    },
    {
      "description": "IT之家 - linux标签 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "125931081906472960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ithome.com/tag/linux",
      "title": "IT之家 - linux标签",
      "type": "feed",
      "url": "rsshub://ithome/tag/linux"
    }
  ]
}
```
