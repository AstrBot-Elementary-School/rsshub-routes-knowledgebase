# 品葱 - 话题

## Coverage
`index-only`

## Route
- Namespace: `pincong`
- Namespace Name: `品葱`
- Route Path: `/pincong/topic/:topic`
- Route Name: `话题`
- Example: `/pincong/topic/美国`
- URL: `pincong.rocks`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `zphw`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: 话题，可在官网获取


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `pincong.rocks/topic/:topic`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/pincong/topic/美国",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "topic.ts",
  "maintainers": [
    "zphw"
  ],
  "name": "话题",
  "parameters": {
    "topic": "话题，可在官网获取"
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "pincong.rocks/topic/:topic"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "品葱 - 兲朝浮世绘 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "104627406254034944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pincong.rocks/topic/%E5%85%B2%E6%9C%9D%E6%B5%AE%E4%B8%96%E7%BB%98",
      "title": "品葱 - 兲朝浮世绘",
      "type": "feed",
      "url": "rsshub://pincong/topic/%E5%85%B2%E6%9C%9D%E6%B5%AE%E4%B8%96%E7%BB%98"
    }
  ]
}
```
