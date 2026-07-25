# 風傳媒 - 频道

## Coverage
`index-only`

## Route
- Namespace: `storm`
- Namespace Name: `風傳媒`
- Route Path: `/storm/channel/:id?`
- Route Name: `频道`
- Example: `/storm/channel/2`
- URL: `storm.mg`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `dzx-dzx`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: ID，可在 URL 中找到


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
  - `storm.mg/channel/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/storm/channel/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "channel.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "频道",
  "parameters": {
    "id": "ID，可在 URL 中找到"
  },
  "path": "/channel/:id?",
  "radar": [
    {
      "source": [
        "storm.mg/channel/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "風傳媒 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "157556838203262976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.storm.mg/api/getArticleList",
      "title": "風傳媒",
      "type": "feed",
      "url": "rsshub://storm/channel/2"
    }
  ]
}
```
