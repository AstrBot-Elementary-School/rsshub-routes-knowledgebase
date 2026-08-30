# 故事 FM - 播客

## Coverage
`index-only`

## Route
- Namespace: `storyfm`
- Namespace Name: `故事 FM`
- Route Path: `/storyfm/episodes`
- Route Name: `播客`
- Example: `/storyfm/episodes`
- URL: `storyfm.cn/episodes-list`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `episodes.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `storyfm.cn/episodes-list`
  - `storyfm.cn/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/storyfm/episodes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 38,
  "location": "episodes.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "播客",
  "parameters": {},
  "path": "/episodes",
  "radar": [
    {
      "source": [
        "storyfm.cn/episodes-list",
        "storyfm.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "故事FM - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63376766918292480",
      "image": "https://static.storyfm.cn/media/2022/04/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://storyfm.cn/episodes-list/",
      "title": "故事FM",
      "type": "feed",
      "url": "rsshub://storyfm/episodes"
    }
  ],
  "url": "storyfm.cn/episodes-list"
}
```
