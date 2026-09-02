# Google - Update

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/doodles/:language?`
- Route Name: `Update`
- Example: `/google/doodles/zh-CN`
- URL: `www.google.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `xyqfer`
- Source Location: `doodles.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: Language, default to `zh-CN`, for other language values, you can get it from [Google Doodles official website](https://www.google.com/doodles)


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
    "picture"
  ],
  "example": "/google/doodles/zh-CN",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 368,
  "location": "doodles.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "Update",
  "parameters": {
    "language": "Language, default to `zh-CN`, for other language values, you can get it from [Google Doodles official website](https://www.google.com/doodles)"
  },
  "path": "/doodles/:language?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Google Doodles - Powered by RSSHub",
      "errorAt": "2025-05-02T15:53:49.300Z",
      "errorMessage": "[GET] \"https://www.google.com/doodles/json/2026/9?hl=zh-CN\": 404 Not Found\n",
      "id": "64590393280128000",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.google.com/doodles?hl=zh-CN",
      "title": "Google Doodles",
      "type": "feed",
      "url": "rsshub://google/doodles"
    },
    {
      "description": "Google Doodles - Powered by RSSHub",
      "errorAt": "2025-05-02T22:52:17.568Z",
      "errorMessage": "[GET] \"https://www.google.com/doodles/json/2026/9?hl=zh-CN\": 404 Not Found\n",
      "id": "57366193674068992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.google.com/doodles?hl=zh-CN",
      "title": "Google Doodles",
      "type": "feed",
      "url": "rsshub://google/doodles/zh-CN"
    }
  ],
  "view": 2
}
```
