# Ganjing World - Shorts in a channel

## Coverage
`index-only`

## Route
- Namespace: `ganjingworld`
- Namespace Name: `Ganjing World`
- Route Path: `/ganjingworld/channel/shorts/:id`
- Route Name: `Shorts in a channel`
- Example: `/ganjingworld/channel/shorts/1fq5chh3ajo67UNu14uAvfzOp1a80c`
- URL: `www.ganjingworld.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `yixiangli2001`
- Source Location: `channel/shorts.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Channel ID, can be found in channel url


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
  - `ganjingworld.com/channel/:id`
  - `www.ganjingworld.com/channel/:id`
- `target`: `/channel/shorts/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/ganjingworld/channel/shorts/1fq5chh3ajo67UNu14uAvfzOp1a80c",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "channel/shorts.ts",
  "maintainers": [
    "yixiangli2001"
  ],
  "name": "Shorts in a channel",
  "parameters": {
    "id": "Channel ID, can be found in channel url"
  },
  "path": "/channel/shorts/:id",
  "radar": [
    {
      "source": [
        "ganjingworld.com/channel/:id",
        "www.ganjingworld.com/channel/:id"
      ],
      "target": "/channel/shorts/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.ganjingworld.com"
}
```
