# QooApp - Hot Hashtags

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/qoo-app/notes/:lang?/topic/:topic`
- Route Name: `Hot Hashtags`
- Example: `/qoo-app/notes/en/topic/QooAppGacha`
- URL: `apps.qoo-app.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `notes/topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: Language, see the table above, empty means `中文`
- `topic`: Hashtag name without `#`


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
    "anime"
  ],
  "example": "/qoo-app/notes/en/topic/QooAppGacha",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "notes/topic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Hot Hashtags",
  "parameters": {
    "lang": "Language, see the table above, empty means `中文`",
    "topic": "Hashtag name without `#`"
  },
  "path": "/notes/:lang?/topic/:topic",
  "topFeeds": []
}
```
