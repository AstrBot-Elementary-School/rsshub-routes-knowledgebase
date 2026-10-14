# 机核网 - 全部机组推荐

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/topics/recommend`
- Route Name: `全部机组推荐`
- Example: `/gcores/topics/recommend`
- URL: `www.gcores.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `topics-all.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.gcores.com/topics/home`
- `target`: `/topics/recommend`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/gcores/topics/recommend",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 3,
  "location": "topics-all.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "全部机组推荐",
  "path": "/topics/recommend",
  "radar": [
    {
      "source": [
        "www.gcores.com/topics/home"
      ],
      "target": "/topics/recommend"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "在这里分享你的兴趣和创作，与同好深入交流 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "122701146735891456",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gcores.com/topics/home",
      "title": "机组游戏社区 | 机核 GCORES",
      "type": "feed",
      "url": "rsshub://gcores/topics/recommend"
    }
  ],
  "url": "www.gcores.com",
  "view": 1
}
```
