# 网易公开课 - 人间

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/renjian/:category?`
- Route Name: `人间`
- Example: `/163/renjian/texie`
- URL: `163.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `renjian.ts`
- Source Module: `_None_`

## Description
| 特写  | 记事  | 大写  | 好读  | 看客  |
| ----- | ----- | ----- | ----- | ----- |
| texie | jishi | daxie | haodu | kanke |

## Parameters
- `category`: 分类，见下表，默认为特写


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
  - `renjian.163.com/:category`
  - `renjian.163.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 特写  | 记事  | 大写  | 好读  | 看客  |\n| ----- | ----- | ----- | ----- | ----- |\n| texie | jishi | daxie | haodu | kanke |",
  "example": "/163/renjian/texie",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 24,
  "location": "renjian.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "人间",
  "parameters": {
    "category": "分类，见下表，默认为特写"
  },
  "path": "/renjian/:category?",
  "radar": [
    {
      "source": [
        "renjian.163.com/:category",
        "renjian.163.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "人间 - 特写 - 网易新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61939868066130012",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://renjian.163.com/special/renjian_texie/",
      "title": "人间 - 特写 - 网易新闻",
      "type": "feed",
      "url": "rsshub://163/renjian/texie"
    },
    {
      "description": "人间 - 特写 - 网易新闻 - Powered by RSSHub",
      "errorAt": "2026-08-29T08:27:27.212Z",
      "errorMessage": "Failed to fetch\n",
      "id": "67446303963867136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://renjian.163.com/special/renjian_texie/",
      "title": "人间 - 特写 - 网易新闻",
      "type": "feed",
      "url": "rsshub://163/renjian"
    }
  ]
}
```
